 What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.

        PropTypes are used to check and if the proper data type is being passed to the props. They are used to prevent certain bugs from occuring.


Describe a life-cycle event in React?

    The React life-cyle consist of three phases: the mounting phase, the updating phase, and the un-mounting phase. 

    The mounting phase rendered by invoking the render method. the lifecyle method componentDidMount is called here.

    Next is the updating phase. Here setSate is called when you component's state data changes, which sets off another render invocation.

    And last is the un-mounting phase. The component is removed from the screen and componentWillUnmount is called to clean up. 


Explain the details of a Higher Order Component?

        Higher Order Components or HOCs allow us to reuse components logic by having receiving components as an argument that returns a new component.


What are three different ways to style components in React? Explain some of the benefits of each.

    there are three ways to style components in React:
        1. vanilla css
        2. styling libraries
        3  styled components

    Vanilla css has the advantage of familiarity. Styling libraries of a fast modular solution to styling. Styled components offer portability.

