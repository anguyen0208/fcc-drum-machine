# markdown-previewer

Build a Markdown Previewer. This is the third project of [FreeCodeCamp Front End Libraries Certification](https://learn.freecodecamp.org/front-end-libraries/front-end-libraries-projects/build-a-drum-machine/).

This project was built with React.

## Live Demonstration

> <https://anguyen0208.github.io/fcc-drum-machine/>

## Screenshot

![drum-screenshot](https://github.com/anguyen0208/images/blob/master/FCC-Drum-Machine.png)

## Objective

- [x] Build a [CodePen.io](https://codepen.io) app that is functionally similar to this: <https://codepen.io/freeCodeCamp/full/MJyNMd>.

- [x] Fulfill the below user stories and get all the tests to pass. Give it your own personal style. You can use any mix 
of HTML, JavaScript, CSS, Bootstrap, SASS, React, Redux, and jQuery to complete this project. You should use a frontend framework (like React for example) because this section is about learning frontend frameworks. Additional technologies not listed above are not recommended and using them is at your own risk. We are looking at supporting other frontend frameworks like Angular and Vue, but they are not currently supported. We will accept and try to fix all issue reports that use the suggested technology stack for this project. Happy coding!

## User stories

- [x] Should be able to see an outer container with a corresponding `id="drum-machine"` that contains all other elements.

- [x] Within `#drum-machine` I can see an element with a corresponding `id="display"`.
- [x] Within `#drum-machine` I can see 9 clickable drum pad elements, each with a class name of `drum-pad`, a unique id that describes the audio clip the drum pad will be set up to trigger, and an inner text that corresponds to one of the following keys on the keyboard: Q, W, E, A, S, D, Z, X, C. The drum pads MUST be in this order.
- [x] Within each `.drum-pad`, there should be an HTML5 `audio` element which has a `src` attribute pointing to an audio clip, a class name of clip, and an id corresponding to the inner text of its parent `.drum-pad` (e.g. `id="Q"`, `id="W"`, `id="E"` etc.).
- [x] When I click on a `.drum-pad` element, the audio clip contained in its child `audio` element should be triggered.
- [x] When I press the trigger key associated with each `.drum-pad`, the audio clip contained in its child `audio` element should be triggered (e.g. pressing the Q key should trigger the drum pad which contains the string "Q", pressing the W key should trigger the drum pad which contains the string "W", etc.).
- [x] When a `.drum-pad` is triggered, a string describing the associated audio clip is displayed as the inner text of the `#display` element (each string must be unique).

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `react-scripts start`
Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### `react-scripts test`
Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `react-scripts build`
Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
