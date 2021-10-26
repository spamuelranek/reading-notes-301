## State and Props

## Okay, ahhh... Wisconsion and a Broom

## Ummm... No... just no...

## But you said -

## I know what I said. It's just not at all what I meant

## Well, what did you mean?

### [Life Cycle of a React Component](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

- Mounting
  - component creation and insertsion 
  - Events:
    - constructor
    - static getDerivedStateFromProps
    - render
    - componentDidMount
    - UNSAFE_componentWillMount

- Updating
  - when a component is updated or state changes
    - Events:
      - static getDerivedStateFromProps
      - shouldComponentUpdate
      - render
      - getSnapshotBeforeUpdate
      - componentDidUpdate
      - UNSAFE_componentWillUpdate
      - UNSAFE_componentWillReceiveProps

- Unmounting
  - removing a component from the DOM
    - Event:
      - componentWillUnmount

- Events:
  - Constructor
    - called before mounted
    - assign state
      - `this.state`
    - bind event handle methods to an instance
  - static getDerivedStateFromProps()
    - state relies in changes in props
  - render()
    - reads `this.props` and `this.state`
    - should not modify `state`
  - componentDidMount()
    - load anything using a network request
    - init the DOM
  - shouldComponentUpdate()
    - changes default behavior
    - if set to false will not rerender component
  - getSnapshotBeforeUpdate()
    - grabs copy of DOM before rerendering page
  - componentDidUpdate()
    - performs network requests afte a change
  - componentWillUnmount()
    - allows for clean up of the DOMand network requests

### Questions:
1. render
2. constructors are called
3. `constructor`, `render`, `componentDidMount`, `React Updates`, `compoonentWillUnmount`
4. loads using a network request or initializes the DOM 

- [Additional Reading](https://reactjs.org/docs/react-component.html)


### [Props vs States](https://www.youtube.com/watch?v=IYvD9oBCuJI)
- Props
  - similar to arguments of a function
  - help intialize
  - what you want your render to be like
  - passed into a component
- State
  - handled inside a component
  - update depending on interaction
  - can update within component
  - rerenders when state changes

### Questions:
1. You can pass things that you would pass to a function in terms of arguments
2. The big difference is State is internal of the component and can be updated by the component. Props is passed into the component as a static piece of data
3. We rerender when states change in a component
4. additions to forms, counters, and dynamically changing value due to user input


## Things I want to know more about:
- when does UNSAFE come into play
  - and why is it so cool

- how does one use states?



[Return to Home](README.md)

