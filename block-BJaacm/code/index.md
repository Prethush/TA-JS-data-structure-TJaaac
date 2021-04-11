```js
let user = {
  name: 'Arya',
  sibling: ['Robb', 'Ryan', 'John'],
};
let allBrothers = ['Robb', 'Ryan', 'John'];
let brothersCopy = user.sibling;
let usename = user.name;
let newUser = user;
```

1. Memory representation

- Create the memory representation of the above snippet on notebook.
- Take a photo/screenshot and add it to the folder `code`

<!-- To add this image here use ![name](./hello.jpg) -->


2. Answer the following with reason:

- `user == newUser;` // output and reason //True both the variables contains the same memory address of the same object so output will be true
- `user === newUser;` //True both the variables contains the same memory address of the same object so output will be true
- `user.name === newUser.name;` //true because these two variable are non primitive type it contains the memory address of the same object if name key in the object is changed it will be reflected in both the variables
- `user.name == newUser.name;` //true because these two variable are non primitive type it contains the memory address of the same object if name key in the object is changed it will be reflected in both the variables
- `user.sibling == newUser.sibling;` //true because these user.sibling and newUser.sibling points to same memory address so the output will be true 
- `user.sibling === newUser.sibling;` //true because these user.sibling and newUser.sibling points to same memory address so the output will be true 
- `user.sibling == allBrothers;` //false both user.sibling ans allbrother  are non primitive and both vcontains memory address of different object so the output will be false
- `user.sibling === allBrothers;` //false both user.sibling ans allbrother  are non primitive and both vcontains memory address of different object so the output will be false
- `brothersCopy === allBrothers;`//false both variables are non primitive and both variable contains memory address of different object so the output will be false
- `brothersCopy == allBrothers;` //false both variables are non primitive and both variable contains memory address of different object so the output will be false
- `brothersCopy == user.sibling;` //true both brothersCopy variable and user.sibling has the same memory adress so the output will be true 
- `brothersCopy === user.sibling;` //true both brothersCopy variable and user.sibling has the same memory adress so the output will be true 
- `brothersCopy[0] === user.sibling[0];` //true both the brotherCopy variable and user.sibling key contains same value so the output will be true
- `brothersCopy[1] === user.sibling[1];` //true both the brotherCopy variable and user.sibling key contains same value so the output will be true
- `user.sibling[1] === newUser.sibling[1];`//True both the variables contains the same memory address of the same object so output will be true
