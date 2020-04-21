# Array and Object Level 2

## writeCode

- Using the different way of accessing and assigning a value to the object using `.` or `[]`

```js
// your code goes here
accessing->object[key];
assigning->object.key = value;
```

- Define a variable named `user` and assign a blank object to it.

```js
// your code goes here
let user={};

```

- Add a key of `user name` and a value of `Black Panther` to that object. (don't remove the space between user and name)

```js
// your code goes here
user['user name'] = 'Black Panther';
```

- Using `console.log` log the value of `user name` key from the user object.

```js
// your code goes here
console.log(user['user name']);
```

- Add a key of the value of variable `batch` in the object with the value of 10. `var batch = "myBatch";`

```js
// your code goes here
user.batch = 10;
```

- Using the alert function alert the value of the key added above.

```js
// your code goes here
alert(user.batch);
```

- Add a key of `42` to the object with a value of `The answer to the meaning of life 🧸`.

```js
// your code goes here
user[42] = `The answer to the meaning of life 🧸`;
```

- Add a new key named `clothing` and value will be a blank object.

```js
// your code goes here
user.clothing={};

```

- Add a property to the value of `clothing` key named `jeans` with the value of 10.

```js
// your code goes here
user.clothing.jeans = 10;
```

- Add another key to clothing with key `shirts` with the value 6.

```js
// your code goes here
user.clothing.shirts = 6;
```

- Change the `shirt` key value to 12.

```js
// your code goes here
user.clothing.shirts = 12;
```

- Access a property named `siblings`. If the property doesnot exist log `Tere are no siblings to this user`

```js
// your code goes here
if(user.siblings){
    user.siblings
}else {
    console.log(`Tere are no siblings to this user`);
}
```

- Add a value of an array to the key `siblings` key. Array will be `["Robb","Ryan"]`
user.siblings = ["Robb","Ryan"];

- Access the first index of the sibling.
user.siblings[0];

- Add another value to the key `siblings` array `"Bran"`
user.siblings.push("Bran");

- Log the last entered value
console.log(user.siblings);

- Log the length of the `siblings` array
console.log(user.siblings.length);

- Change the last value `siblings` array to `"John"`
user.siblings[length-1]= "John";
