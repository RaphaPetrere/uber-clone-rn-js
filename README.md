<div style="display: flex; justify-content: center; align-items: flex-end; margin-bottom: 2rem">
  <img src="https://links.papareact.com/gzs" style="width: 400px">
  <h2>clone</h2>
</div>

# Introduction

This is a React Native clone application built with Javascript during this [livestream](https://youtu.be/bvn_HYpix6s).

## Getting Start

This is an app buit with [Expo](https://expo.dev/), so you must have Expo CLI on your computer in order to properly use it.

After installing Expo CLI, you must also have [npm](https://nodejs.org/en/) or [yarn](https://yarnpkg.com/) on your computer in order to download all the dependencies used in the project.

To install those dependencies you must use the following code on your terminal:
```terminal
  npm install
```
or
```terminal
  yarn install
```

After that, just run `expo start` on your terminal and you're finally set to use it.

## Features

Just like Uber, you'll have your usual map, travel from point A to point B but with a new interface and using some famous [techonologies](#techs).

## <a name="techs"></a>Techonologies

Here is the list of some techs used to build this application:

- [Redux Toolkit](https://redux-toolkit.js.org/)
  > Redux Toolkit was used to create a provider to set the Origin, Destination and Travel Time.
  ```terminal
  yarn add @reduxjs/toolkit
  ```

- [Tailwind CSS](https://github.com/jaredh159/tailwind-react-native-classnames)
  > Tailwind was used as the go-to library for stylization since is has some useful features like style   for android-only or ios-only.
  ```terminal
  yarn add tailwind-react-native-classnames
  ```

- [React Navigation](https://reactnavigation.org/)
  > You can't have an app like Uber that weights heavily on navigation without a proper navigation  library. <br>That's where React Navigation comes with its easy to use Stack Navigation option.
  ```terminal
  yarn add @react-navigation/native
  ```

- [Google Autocomplete](https://github.com/FaridSafi/react-native-google-places-autocomplete)
  > To get the locations names and all the most popular places, we used Google Autocomplete connected with all the APIs from GCP like Directions API, Places API and Distance Matrix API.
  ```terminal
  yarn add react-native-google-places-autocomplete
  ```

  * Directions API
    > Used to access routing using an HTTP Request.

  * Places API
    > Get data from the same database used by Google Maps. We are mostly using it for its Place autocomplete feature

  * Distance Matrix API
    > Access travel distance and time for a matrix of origins and destinations. It returns the recommended route between start and end points.
  