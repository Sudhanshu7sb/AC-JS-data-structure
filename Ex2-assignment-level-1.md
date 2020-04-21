# Data Structure Assignments

## writeCode

Follow the instruction and write code just below the instruction.

- Create a variable named `character` using `let` and assign a value of blank object to it.

```js
// your code goes here
let character = {};
```

- Go to this [link](https://awoiaf.westeros.org/index.php/List_of_characters) and choose any charactor you like and click on the link. For example [Arya Stark](https://awoiaf.westeros.org/index.php/Arya_Stark)

```js
// your code goes here
```

- Re-assign the value of `charator` variable to and object with the key `charatorName` and value of the first name of your charactor. example "Arya"

```js
// your code goes here
character = {
  characterName : 'Shella'
}
```

- A variable named `age` is predeined to 20. Add a new key named `character-age` with the value of age variable.

```js
let age = 20;
// your code goes here
character.characterAge = age;
```

- Add a new key named `sur name` with the vlaue of the surname of the cahractor i.e "Stark"

```js
// your code goes here
character.surname = 'Whent';
```

- Add a new key named `title` with the value title of the charactor (you will find in the right side bar) i.e "Lady of Winterfell"

```js
// your code goes here
character.title = 'Lady_of_Harrenhal';

```

- Add another property named `greet` and value should be a function when called should alert `I am [NAME HERE] and my title is [TITLE HERE]`.

```js
// your code goes here
character.greet = function(){
  alert('I am ' + characterName + ' and my title is ' + title);
}
```

- Add a new property named `isFemale` and value will be either `true` or `false` according to the charactor.

```js
// your code goes here
character.isFemale = 'true';
```

- Change the method `greet` to now alert `He is [NAME HERE] and his title is [TITLE HERE]` if the character is male or else `She is [NAME HERE] and her title is [TITLE HERE]`. You should use `if/else`.

```js
// your code goes here
character.greet = function(){
  if(character.isFemale == 'true'){
    alert('She is ' + character.characterName +' '+  'and her title is ' + character.title);
  } else{
  alert( 'He is ' + character.characterName + ' '+ 'and her title is ' + character.title);
  }
}
```

- Add a new method (function inside objects are called methods) named change gender. When called should be able to flip the value of `isFemale`.

```js
// your code goes here
character.changeGender = function(){
  if(character.isFemale == 'true'){
    character.isFemale = 'false';
    alert(character.isFemale);
  } else if(character.isFemale == 'false'){
    character.isFemale = 'true';
    alert(character.isFemale);
  }
}
```

- Check by calling `greet` and see if the message changed or not.

```js
// your code goes here
character.greet();
```

- `let keyName = "playedBy";`- Add a new key with the value stored in `keyName` variable the value of the Played by in right side bar. (use the variable name to do this)

```js
// your code goes here
character.keyName = 'playedBy';
```

- `alert` the value of key stored in `keyName` variable.

```js
// your code goes here
alert(character.keyname);
```

- Write a `for..in` loop to `console.log()` all the key of the object character.

```js
// your code goes here
for(let key in character){
  console.log(key);
}
```

- Write a `for..in` loop to log the all the key value pair seperated by `-` like `charactorName - Arya`.

```js
// your code goes here
for(let key in character){
  console.log(key + ' - ' +character[key]);
}
```

- Using the function `console.log log` the value of the key `42`.

```js
// your code goes here
```

- Add a key in your object with the value of the variable `city`. The value of the key should be `true`.

```js
// your code goes here
character.city = 'true';
```

```js
var city = prompt("Enter the city name you visited las time.");

// your code goes here
```

- Uisng console.log log the value of the key defined above.

```js
// your code goes here
```

-. Can you define a key of `let or var` in any object? Reason.

```js
// your code goes here
```

## writeTextAnswer

```js
let keyValue = "username";
let charactor = {
  username: "arya"
};
// 1.
console.log(charactor["keyValue"]);
// 2.
console.log(charactor[keyValue]);
```

- What will be the output of 1 and 2.
output of 1 is undefined 
output of 2 is arya
- Why are they different.
1 
- Can I use `.` dot notation to access the value (using variable name). Write reason.
- What is the difference between `.` dot notation and `[]` bracket notation. Example
- What are situation where we use dot notation and bracket notation.

## writeQuiz

Whic statement is true?

- [x] You can replace all dot notation with bracket notation.
- [ ] You can replace all bracket notation with dot notaiton.

## Array-writeCode

- Create an array named colors that contains five different names of colors as strings.

```js
// your code goes here
let colors=["blue","black","white","green","red"];
```

- Access the first color in the array and print it to the console using `console.log()`

```js
// your code goes here
console.log(colors[0]);
```

- Now do the same with the third color in the list.

```js
// your code goes here
console.log(colors[2]);
```

- Re-assign the value of the last color in array to "ultraviolet".
//FEEDBACK : it should be assign instead of re-assign

```js
// your code goes here
colors[colors.length-1] = "ultraviolet";
```

- Re-assign the value of the last color in array to "ultraviolet". This time use `arr.length` property to know the length of the array.

```js
// your code goes here
colors[colors.length-1] = "ultraviolet";
```

- Create a new variable called fourthColor and set it equal to the fourth color in the list.

```js
// your code goes here
let fourthColor = colors[3];
```

- Add another color to the end of the list. (use array method called push)

```js
// your code goes here
colors.push("maroon");
```

- Add another color to the beginning of the list. (use unshift)

```js
// your code goes here
colors.unshift("yellow");
```

- Print the length of the array to the console with `console.log()`

```js
// your code goes here
cosole.log(colors.length);
```

- Remove the last color from the end of list, and then print the length of the array to the console one more time.

```js
// your code goes here
colors.pop();
console.log(colors.length);
```

- Write a for loop to iterate through every color in the array and print each color's value to the console.(use for loop)

```js
// your code goes here
for(let i=0;i<colors.length;i++){
    console.log(colors[i]);
}
```

- Write a for loop to iterate through every color in the array and print each color's value to the console.(use for..in)

```js
// your code goes here
for (let i in colors){
  console.log(colors[i]);
}
```

- Write another loop to display the value and key of array in this format. `The value for index 0 is Red` for each value.

```js
// your code goes here
for (let i in colors){
  console.log('The value for index '+i+' ' + 'is '+ colors[i]);
}
```

- Create a variable named `lastColor` that will always point to the last element of the colors array, no matter how many colors are in the list.

```js
// your code goes here
let lastColor =colors[colors.length-1];
```

- Add a new color `tomato` to the index 45. And check the length of the array. Use `console.log` to print.

```js
// your code goes here
colors[45] = "tomato";
cosole.log(colors.length);
```

## writeTextAnswer

What will be the output if you access index greater than the length of the array. Like array length is 10 and `arr[11]`. Same with object if you access the key that doesnot exist.

output will be undefined
