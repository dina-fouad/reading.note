## React - Forms

- What is a ‘Controlled Component’?

React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way .

- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

 the input’s value is always driven by the React state. While this means you have to type a bit more code, you can now pass the value to other UI elements too, or reset it from other event handlers.

 - How do we target what the user is entering if we have an event handler on an input field?

 When you need to handle multiple controlled input elements, you can add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.


 