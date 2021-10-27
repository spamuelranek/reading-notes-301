## Please fill out this form

## Is it responsive?

## Some say it *React*s

# React and Forms

### [Forms](https://reactjs.org/docs/forms.html)
1. What is a ‘Controlled Component’?
- A controlled Component is an input form element whose value is controlled by React - *https://reactjs.org/docs/forms.html*
2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
- We should wait to store users responses onSubmit. This allows for users to modify data before submission and it does not require rerendering every keystroke.
3. How do we target what the user is entering if we have an event handler on an input field?
``` js
<form onSubmit ={this.handleSubmit}> // this will run handleSubmit() on submit of the form
    <input type ="text" value={this.state.value} onChange ={this.handleChange}> /> //this runs handleChange every keystroke
    <input type ="submit" value ="Submit"/> // this is the event that onSubmit is listening for
</form>
```

### [Conditional(Ternary) Operator](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)
1. Why would we use a ternary operator?
- We would use it to make-one liners, which after practice will become easier to read even faster
2. Rewrite the following statement using a ternary statement:
```js
if(x===y){
    console.log(true);
} 
else {
    console.log(false);
}
```
```js
const z = x===y ? console.log(true) : console.log(false);
```

## Things I want to know more about:
- what other one-liner forms are there to start learning to read
  - the arrow function and the ternary Operator seem to be a destinct trend to simplify or condense down the information


[Return Home](README.md)