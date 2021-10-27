## Give me some Props

## Hey, Man you are looking good today!

## No, like properties

## One of the railroads work?

## How can you be so lost everytime?

## I'm just a child, you told me I couldn't pass anything to you

## HMM... you are right... this time...

## *smiles*

# Map() Function, Spread Operator, Passing Functions

### [React Docs - Lists and Keys](https://reactjs.org/docs/lists-and-keys.html)
1. What does .map() return?
- Returns a manipulated array
2. If I want to loop through an array and display each value in JSX, how do I do that in React?
``` js
let array = [x,y,z];
let newArray = array.map(element =>(<li>{element}<li>));
```
3. Each list item needs a unique ____.
- Each list item needs a unique key
4. What is the purpose of a key?
- Allows for extraction of data from with in the list items

### [How to Use the Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)
1. What is the spread operator?
- `...array`
2. List 4 things that the spread operator can do.
  1. Copy Arrays
  2. Concatenating Arrays
  3. Using an array as arguments
  4. Adding to state in React
3. Give an example of using the spread operator to combine two arrays.
``` js
let myArray =['x','y','z'];
let yourArray = [1,2,3];
let ourArray = [...myArray,...yourArray];
console.log(ourArray); //['x','y','z',1,2,3]
```
4. Give an example of using the spread operator to add a new item to an array.
```js
let numbers =[1,2,3];
let moreNumbers = [...number,4,5];
console.log(moreNumbers); // [1,2,3,4,5];
```
5. Give an example of using the spread operator to combine two objects into one.
```js
let firstCarMake = {make: 'Kia'};
let firstCarModel = {model: 'Rio'};
let firstCar = {...firstCarMake, ...firstCarModel};
console.log(firstCar); //{make: 'Kia', model: 'Rio'}
```
###[How to Pass Functions between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)
1. In the video, what is the first step that the developer does to pass functions between components?
- Creates the function in the Parent Function
2. In your own words, what does the increment function do?
- The increment functions loops through the array of people. It checks to see if the paramemter name that is passed into the method is the same as one of the names in the people array. If it is it increments the count by one inside that object. It then returns the objects into the variable ppl. Then using setState() it sets all of people to the ppl array. Thus triggering a rerender due to state change. 
3. How can you pass a method from a parent component into a child component?
- You treat it like any other prop except you call it `passedMethod ={this.method()}`. In the child the method will be named `passedMethod`
4. How does the child component invoke a method that was passed to it from a parent component?
- Using the example from above `this.props.passedMethod();`. This will invoke the method of the parent function.

## Things I want to know more about:
- Reading the lifting of states did not quite click
  - I think i need to diagram it to be able to see the interaction.

[Return Home](README.md)