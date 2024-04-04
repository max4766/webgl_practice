# Introduction

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

This is a web page shows a 3D model with a background.

You can control the model's orbit and see the model since it provides you with light effect.

`webGL` is a method to show 3D models on a web.

Since it's a bit difficult to use, `three.js` is used for managing codes easier.

and `drei`, `fiber` are React optimized version of three.js.

With drei and fiber, you can build up a webpage with 3d models easier and faster than just using three.js.

Here, the 3D model was created solely byself using `SketUp`, one of the 3D modeling tools.

## Getting Started

First, copy this project's URL and clone this project into your local with git :

```bash
git clone [project URL]
```

FYI, No need to make a new folder for this project. 

it is already packed in the folder with it's project name when you clone.

Then, recover packages. update node_modules with the command below :

```bash
npm install
```

Next, run the development server with one of the commands below (npm recommended) :

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

Congratulations! you can now see the view of this project! 

## About the source

- `src/App.js` : all the components are pre-built with `drei` and `fiber`.

Environment, OrbitControls are possible thanks to drei.

uploading 3D models are possible thanks to fiber.

Here, there are no extra components defined in the directory but App.js.

## Goal

The goal of this project was `To show a 3D model with a website using webGL but faster and easier`

It was possible because React uses components and drei and fiber are a componented way of three.js.

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
