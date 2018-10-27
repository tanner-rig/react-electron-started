# README #

This is a starter app for developing Electron apps using React.js.  This app used create-react-app to begin.

### Developing ###

* git clone git@bitbucket.org:tmrigby/electron-react-starter.git
* npm install
* npm run dev (this will open a browser window as well as the electron window, because for dev purposes we have to run a dev server)

### Packaging App ###

* npm run build
* npm run package <App Name> (if you dont specify the app name electron-packager assumes the name from package.json)

App folder will appear within directory, and the app will be inside the folder.