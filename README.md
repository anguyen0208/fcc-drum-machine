# Drum Machine

Build a Drum Machine. This is the third project of [FreeCodeCamp Front End Libraries Certification](https://learn.freecodecamp.org/front-end-libraries/front-end-libraries-projects/build-a-drum-machine/). The project was built with React.

Check for [Live Demo](https://anhnguyen.page/fcc-drum-machine/)

## Screenshot

![drum-screenshot](https://github.com/anguyen0208/Project-Screenshots/blob/master/FCC-Drum-Machine.png)

## Objective

- [x] Build a [CodePen.io](https://codepen.io) app that is functionally similar to this: <https://codepen.io/freeCodeCamp/full/MJyNMd>.

- [x] Fulfill the below user stories and get all the tests to pass. Give it your own personal style. 

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

### `npm start`
Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### `npm test`
Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm build`
Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
