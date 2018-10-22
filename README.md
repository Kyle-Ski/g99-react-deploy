# Deploying a React app with Surge

1. Make sure you have surge install globally
 - `npm install -g surge`

2. Run the Create React App build
 - `cd your-react-project`
 - `npm run build`

3. Change into build directory
 - `cd build`

4. Run surge
 - `surge`

### Adding deploy script into package.json
 - In ```package.json``` under "scripts" add this line:
 ```
 "deploy": "npm run build && surge ./build/ [your domain name for surge].surge.sh"
 ```
 - ```npm run deploy``` will need to be ran from your project root, not the build directory
## Technologies
 - React built with Create-React-App
 - CSS Animation adapted from [this pen by Mark Thomes](https://codepen.io/WithAnEs/pen/OVZRvg)


 ## The deployed link for my app is at this [link](http://stormy-effect.surge.sh/)