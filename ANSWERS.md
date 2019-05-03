 1) What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.

 PropTypes are used to check what type of data a react component needs to render properly. Putting checks in place before we write code gives us check in place that allow us to make mistakes without repercussions. 

 2) Describe a life-cycle event in React?

 Life-cycle events are functions that execute at different points in a components run time. There are three time intervals where functions are executed. They are called the mounting, updating and unmounting phase.

 3) Explain the details of a Higher Order Component?

 A higher order component is a function that takes in a component and returns a new component with added functionality. HOC allow us to reuse code and apply it to multiple components.

 4) What are three different ways to style components in React? Explain some of the benefits of each.

 Css Stylesheets - Stylesheets allow us to import css files into a component so we can have a separate  file for each.

 Inline Styling - Inline styling allows for quick changes directly on your Component import declaration.

 Styled Components - Allows for styling in JS directly in the component file. This keep everything in one place. Because Styled Components are HOCs you can give the final component a unique name and get rid of existing classNames.  