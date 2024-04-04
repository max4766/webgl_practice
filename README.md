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
npm install
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

Congratulations! you can now see the view of this project! 

## About the source

- `src/components/Header.js` : This is the part where Navigationbar compromises using MUI components.

even if you click the items, it won't redirect to other pages yet it shows the name of what each icon stands for.

- `src/components/Main.js` : Main page where MainBarChart.js and MainDatasheet.js contents are mingled up in MUI grid component.

- `src/components/MainBarChart.js` : Barchart. Data is defined here. It doesn't get data from other servers.

this shows how recharts UI looks like.

- `src/components/MainDatasheet.js` : Datasheet. As a default, you can add items by click Add button in a combination with adjusting rows input.

there is no option to save data here.

## Goal

The goal of this project was `To swiftly ideate a concept with ready-made components with React and MUI`.

this project has taken only less than an hour thought it takes a huge amount of time if you markup without framework and library.

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
