# React Menu Bar

This app is intended to give you a really quick starting place with a menubar app built with React and all the ES6 goodness. It's all made possible by the good work done on [MenuBar](https://github.com/maxogden/menubar) and [Parcel JS](https://parceljs.org/)

## Running the app

```shell
$ yarn start
```

## Developing

If you are developing then you'll need to run a few commands to bundle the JS. Depending if you are making changes to the backend (electron) or the frontend (react) there are 2 different commands to run. Of course if you are working on everything then run both. 

_Electron_
```shell
$ yarn watch:electron
```

_React_
```shell
$ yarn watch:react
```

## Environment

There are only 2 environment settings however the `.env` file can be used for other settings that your app may need. 

Before starting the app run.
```
$ cp .env.example .env
```

```
APP_SLUG="react_menubar" // lowercase and underscore separated.
APP_NAME="React MenuBar" // Friendly name
```