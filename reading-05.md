## Levels of abstraction

## Oh like a cuil

## A cuil?

## Yeah you know like "Let's let cuil be one level of abstraction from reailty"

## No, I do not know what you refer to

## Oh this is a weird thing that popped up on Reddit in the early tens'

## Well... this is not that specifically but it does deal to some extent of removing an object from its concrete counterparts


# Putting it all together

### [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)
1. What is the `single responsibility principle` and how does it apply to components?
- `single resopsibility principle` is the ideal of only do one thing per function or object. This applies to components by trying to make sure each component has only one task.
2. What does it mean to build a ‘static’ version of your application?
- It means to build a none interacticve version kinda like a rendered wireframe
3. Once you have a static application, what do you need to add?
- To identify the minimum  about of mutable states required to have the behavior desired
4. What are the three questions you can ask to determine if something is state?
  1. Is it pass from a parent via props?
  2. Does it remain unchanged over time?
  3. Can you compute it based on other states or props in your component?
5. How can you identify where state needs to live?
  1. What components need the information in state to render?
  2. What is a common parent for all components that need that state?
  3. If there is no single component that makes sense to own that state, make a new one


### [Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)
1. What is a “higher-order function”?
- `higher-order function` either takes in a function or returns a function
2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
- it returns a simple function where `m` is given to the function and checks if `m` is greater than the argument `n`. It is a case where f(n) is encapsulated in f(m). When f(m) is executed it uses f(n) where n is already defined and compares m to it.
3. Explain how either map or reduce operates, with regards to higher-order functions.
- map does not require a function but it can take one in as an argument in order to transfor an element with in the array the map is iterating over. It applies the function to the element to create a different but related element in the new array.

## Things I want to know more about:
- What is the difference between a higher-order function and a callback function? In the last example it seemed to be the same thing. With a small search online came back with them being similar but different in somewheres