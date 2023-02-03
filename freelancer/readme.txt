 Write the following code in the terminal to listen to scss: 
 node-sass -w sass -o public/css

 or:

 npm run sass

ctrl+c stops listening in terminal


"scripts": {
    "sass": "node-sass -w sass -o public/css --output-style compressed"
  },


  "--output-style compressed" compress css files