# WHO DARES TO, TO, TO DISTURB MY SLUMBER OF TWO WEEKS?
# I HAVE PROCESSED NO INFORMATION AT ALL FOR THE LAST TWO WEEKS.
# WHY HAS THIS NULL EXPERIENCE ENDED?

## We must learn of React if we are to progress further in these classes

# FINE. WHAT IS ON THE DOCKET TODAY SCRIBE?

## Today we start with:

### [Component-Based Archiecture](https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm)
#### Component
  - well-defined communication interfaces containing:
    - methods
    - events
    - properties
  - modular
  - portable
  - reusable

#### Views
  - Object-oriented
    - one or more cooperating classes
      - problem domain class (analysis)
      - infrastructure class (design)
      - requires defining the interfaces that enable classes to communicate
  - Conventional 
    - funtional element
    - module of a program
  - Process-related
    - creates a sysetem from existing components from a library
    - ui:
      - grids
      - buttons
      - utility components
        - expose funitions used in other components
      - resource intensive
      - not frequently accessed
      - require JIT(just-in-time)

#### Characteristics of Components
- Reusability
- Replaceable
- Not context specific
  - generalize the function
- Extensible
  - can be extended from existing components to preform new things
- Encapsulated
  - self-contained
- Independent
  - minimal dependencies

#### Principles of Component-Based Design
- Guidelines:
  - small reusable units
  - has its own interface of required ports and provided ports
  - can be extended without need to change other code
  - depend on abstraction components vs concrete components
  - Connectors connected components, have rules that are governed byby the interafces of the components
  - Components Interatction:
    - method invocations
    - asynchronous invocations
    - broadcasting
    - message driven
    - data stream communications
  - server class 
    - specialized interfaces should cater to most categories of clients
  - components can extend to other components but can still offer its own extension points

#### Component-Level Design Guidelines
- naming conventions for components are part of the architectural model
  - architectural component names  come from the problem domain and have meaning to all stakeholders.
  - extract entities that can exist independently
    - create foundations that do not require other pieces
  - create these entities as new componenets
  - infrastructure componenet names should relect ther implementation-specific meaning
  - should model dependencies from left to right and top to bottom
    - Top being base class
    - Bottom being derived classes
  - should model any COMPONENT dependencies as intrefaces  not a component to component dependency

#### Conducting Component-Level Design
- Recognizes all design classes from the infrastructure domain
- Descriges al design classess that are not axquired as reusable components
- Identifies interfaces, attributes, and data types and structures for implementation for each component
- Descirbes processing flow in deatail by psuedo code or UML diagrams  
- Describes persistent data sources and classes to manage them
- Elaborates behavioral representations for a class of component
- Elaborates additiona implementation detail
- ? Deomonstrates the location of key packages or classes of components in a system by using class instances and designating specific hardware and operating system environment ?
- Using these guideline are a good starting point
  - The more experienced you are, the further a field you should be checking for alternative options before locking in a specific design model

#### Advantages to Component-Level Desing
- Ease of Redeplyment
- Reduced cost
  - using third party components
- Ease of development
  - decrease impact to other parts of the system
- Reusable
- Modification of technical complexity
  - ? a compont modeiries the complexity though the use of a component container and its services?
- Reliability
- System Maintenane and evolution
  - allows for incremental change
- Independent
  - designed with separate components from the outset


# IS THERE MORE FOR TODAY?

## Aye, There be a discussion of "Props"

# SO THERE IS, SO IT WILL BE

### [What is Props](https://itnext.io/what-is-props-and-how-to-use-it-in-react-da307f500da0)
#### What is Props?
- Props is properties
  - used for passing data from one component to another
- Dataflow is one directional
  - Parent to Child
- Props is read-only
  - new component should not change the in coming inforamtion

#### Using Props in React:
1. define attribute and value
2. pass it to child components by using props
3. render Props data


## Things I want to know more about:
- conventional view
- does not expose details of interal process
  - hides it detailed implementation
- abstraction components vs concrete components
- interfaces in relationship to components
- UML Diagrams

[Back to the Top of al inFormation](README.md)