# EXP:02 Javascript-Looping
### PROGRAM

### Looping through an array
```
const fruits = ["apple", "banana", "cherry"];
for (let i = 0; i < fruits.length; i++) {
  console.log(fruits[i]);
}
```
### Looping through an object
```
const person = {
  name: "John",
  age: 30,
  city: "New York"
};
for (const key in person) {
  console.log(person[key]);
}
```
### Looping through an array of objects using direct access of object properties
```
const students = [
  { name: "Alice", age: 25 },
  { name: "Bob", age: 30 },
  { name: "Charlie", age: 22 }
];
for (let i = 0; i < students.length; i++) {
  console.log(students[i].name + ", " + students[i].age);
}
```
### Looping through an array of objects using dynamic key names
```
const books = [
  { title: "The Catcher in the Rye", author: "J.D. Salinger" },
  { title: "To Kill a Mockingbird", author: "Harper Lee" },
  { title: "1984", author: "George Orwell" }
];
for (let i = 0; i < books.length; i++) {
  for (const key in books[i]) {
    console.log(key + ": " + books[i][key]);
  }
}
```
### OUTPUT
![image](https://github.com/Rohith-AIDS/javascript-looping-exp-02/assets/94980736/baa33c23-8210-433d-a70c-e40d31a08499)
