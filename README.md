# video-bodypix

This application uses the body-pix library, in conjunction with tensorflow, to create a virtual background function. Essentially, a video-feed is collected and segmented, using the body-pix library, and this segmentation is overlaid on an html5 canvas, which is then placed on a background. This produces a 'green screen' effect basically. This implementation is quite rudimentary, however, and allows for the creation of additional features, such as extra backgrounds and all that. This application is built in react. To use it, simply clone the repo and run an -npm start. 
