# Progressive Web Apps - What, Why, & How
Speaker: Jennifer Bland
Notes written by: Yassine Jaoudi

### Four requirements for progressive web apps:
* HTTPS (It needs to be safe)
* IBDB
* Provides security against: Wiretapping, man-in-the-middle attacks.

### Web App Manifest (all the following content could be placed in the Manifest.json):
* <link rel="manifest" href="manifest.json">
* display
* backgroumd_color - expected background color for the web application
* theme_color - default theme color for an application
* icons - an array of image objects that can serve as app icons in various contexts 
* Orientation - can enforce a specific orientation for instance( landscape or ...)

### Service Worker:
* Background script to serve network or cached content
* First thing register your server work
* Install it
* Activate it (*using event listener (check this website to learn about what is event listener : https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)*)
* Fetch (give command to go and grab the data from the back end and show it to the user in the front end)

### Responsive Design:
* can be installed on any device

### PWA checklist in the following URL:
* https://developers.google.com/web/progressive-web-apps/

### PWA Perermonce:
* Lighthouse (*She recommend to not use the google' website, instead use the lighthouse google extension for feedback and measure*)

### The responsive design (diyz website):
* Used a grid format (*for refernce check out CSS Grid in the mozilla documentation, they have amazing contents.*)
