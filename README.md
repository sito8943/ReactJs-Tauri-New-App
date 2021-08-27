For more information look here [https://dev.to/krofax/creating-desktop-apps-with-reactjs-using-tauri-af] https://dev.to/krofax/creating-desktop-apps-with-reactjs-using-tauri-af

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).
To learn React, check out the [React documentation](https://reactjs.org/).

To learn Tauri, check out the []

# ReactJs + Tauri

## Using npm
`npm install`

## using yarn
`yarn`

# Defining Tauri

`{ // Add Tauri to the script object "scripts": { "tauri": "tauri", "dev": "npm run tauri dev", "bundle": "tauri build", }`

`npm run Tauri init`

# Building

## builds our react app
`npm run build`

## builds the Tauri crates
`npm run bundle`

Note: The first time you run this, it will take some time to collect the Rust crates and build everything, but on subsequent runs, it will only need to rebuild the Tauri crates which is much quicker.
