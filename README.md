# React Simple boilerplate

[![Greenkeeper badge](https://badges.greenkeeper.io/corlaez/react-simple.svg)](https://greenkeeper.io/)

An opinionated react boilerplate with Parcel as a bundler.

Want to see simpler examples with explanations? [Checkout my parcel examples](https://github.com/lrn2prgrm/parcel-examples)

## Features

[Parcel](https://parceljs.org/), [Hot module replacement](https://parceljs.org/hmr.html), [React](https://reactjs.org/), [Redux](https://redux.js.org/), [Jack Tsu inspired redux pattern](https://jaysoo.ca/2016/02/28/organizing-redux-application/), [Redux Logic](https://github.com/jeffbski/redux-logic) (TODO)

## Use it:

* Run with `yarn start`
* Go to `https://localhost:1234`

## Known issues

I have had troubles to add Hot Module Loader to Parcel (namely it spitted a console error and didn't provide any additional feature). So it is not included.

As a consecuence this project doesn't include the feature of re run every past action against the new reducers, reducers get replaced but only future actions will run through the new reducers.

This project does hot reload redux code and relies on keeping the redux store on window global. I am not sure if this could cause problems in more complex apps.
