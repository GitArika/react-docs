# Vite

Next Generation Frontend Tooling for websites.

## Pre requisites

You may need nodejs to create a react app. Personaly I recommend you to use a version manager such as nvm.

## Create your project

```sh 
npm create vite@latest
```
It will ask you the **project name** and **template** to be used.

## Run your project

```sh 
npm run dev
```

It will hot refresh your app in every change.

## Folder structure

### src

**src** folder contains all your react app files, including the main component, an app component, styles and assets. 

### package.json

That file will reference all your external dependencys, you can use **npm install** to get dependencys into node_modules.

Usually it's not tracked by git.

### index.html

Index file that will be loaded in browser and it contains a div tag with an id **root*.

It uses ReactDOM library behind the scenes so your components are dinamically build at client side using javascript.

### vite.config.js

### .gitignore

Files that will not be tracked from git source code version manager.