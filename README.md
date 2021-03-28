This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## [Live Demo of Amazon Clone App](https://clone-8db63.web.app/)

Deployed on Firebase

## Start template

- npx create-react-app amazon-clone
- Then go firebase create a new project
- cd to correct folder `cd amazon-clone`
- `npm start`
- go firebase then create web app
- In local console `npm install -g firebase-tools`
- create `firebase.js` in `src`
- Select config and paste snippet code of Firebase SDK in to `firebase.js`
- remove App.test.js, logo.svg, setupTests.js
- go App.js remove all thing under also include <header> and import logo part
- remove all in `App.css`
- go `index.css` select \* set margin to 0
- create Header.js and type rfce
- [material-ui](https://material-ui.com/)
- install material-UI `npm install @material-ui/core`
- `npm install @material-ui/icons`
- `npm install react-router-dom`
- `npm i react-currency-format`
- build the price total counter and basket checkout with remove function
- build Authentication by firebase, 1st layout
- go to Authentication in firebase enable sign in method email
- open new terminal `cd amazon-clone` folder and `npm i firebase`
- `import firebase from "firebase";` in firebase.js
- done sign in & out page and User Authentication
- deploy online
- `firebase login` to login firebase
- `firebase init` then select `hosting` -> use an existing project -> (public) build
- `npm run build` create production build, if make any changes in app you have run this again
- `firebase deploy`
- checkout page (payment page) with stripe frontend
- Cloud function to process stripe payment (serverless)
- Firebase for real-time database (Firestore)
- MERN stack
- Build the "my order" page
- Store orders for logged in user
- cd amazon-clone and `npm i @stripe/stripe-js` & `npm i @stripe/react-stripe-js`
- Blaze plan on firebase
- create stripe account and get test API key
- `npm i axios`
- `firebase init` -> function -> JS
- src is app (front-end), functions (full back-end)
- `cd functions` -> index.js to build a express app host on cloud function
- `npm i express`, `npm i cors`, `npm i stripe`
- copy secret key from stripe
- `firebase emulators:start`
- click functions[api] and emulator UI
- card number enter 424242....
- check payment in stripe that you receive the money
- push order into database, go firebase -> cloud firestore -> test mode
- `cd amazon-clone`, `npm install moment`
- `firebase deploy --only functions` only deploy the functions (back-end)
- see spark on bottom of firebase page, select Blaze
- then go firebase -> Functions grab the api link inside paste into axios
- cd to amazon-clone: `npm run build`
- `firebase deploy --only hosting` (hosting: front-end, functions: back-end)

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
