# Simple To Do app using React 

### Built following recipe from https://medium.freecodecamp.org/how-to-build-a-todo-list-with-react-hooks-ebaa4e3db3b

The app doesn't use ES6 classes because:

* Isolating stateful logic, making it easier to test.
* Sharing stateful logic without render props or higher-order components.
* Separating your app’s concerns based on logic, not lifecycle hooks.
* Avoiding ES6 classes, because they’re quirky, not actually classes, and trip up even experienced JavaScript developers