# Nimbus 3D



Thingiverse Clone for 3D Printing STL files.

Deployment: https://nimbus-3d.herokuapp.com/

Log-In: Due to the API restrictions you must login with a Thingiverse account and only up to 10 people can access the site at this time.



### Thingiverse API:

https://api.thingiverse.com

### Goals/Features:

The goal of the app is to make a clone of Thingiverse and fix some of the issues i have experienced with the site. One of the biggest issues is that Thingiverse does not keep track of the page you are in so when you click a model and want to go back to search results it will take you back to the first page instead of the page you were in. This can be a nuisance when you are on a page such as 30 + and now you have to start from the beginning.  

The second goal was to change the recommendations on the home page. On the Thingiverse site it is set to display the most popular models in the past 30 days. This leads to the front page being the same models for a long time. I have changed it to show the most popular in the last 3 days so that it changes more often while still leaving the option to view models popular in the last 7,30 or 365 days.

Lastly, I added a button to the model page that will download all the model files only. On the Thingiverse site it will download all extra files including images. I find this unnecessary for most models and downloading each file individually might not be optimal if there are a lot of files for one model. The download all button on this app takes care of that and still allows the user to download the files individually if needed.



​		App Created Using: React Redux, CSS, Material-Ui, HTML, Javascript









# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
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

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
