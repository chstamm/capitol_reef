# Capitol Reef Remote Website Test

### The test website can be visited at [this Netlify website](https://capitolreef-remotetest.netlify.app/index.html).

**THE PROJECT:** I helped build a website for Capitol Reef that could work independently from the World Wide Web. The idea was to create an informative and interactive website to work on Spark Beacons placed in parts of the park, mainly around the ruins of Sleeping Rainbow Ranch, so that visitors could be able to learn more about the locations and see more information about the park.  

**The Challenge:** Along with creating the website to be remote, we also wanted to integrate an already built project for Capitol Reef, which can be found in the capitolReefAR file. This project wasn’t ready to be remote because it was getting information from other sites, such as js files, font files, and other links. 

**The Learning Experience:** I learned to manage files sizes without losing too much quality while making sure that the website will work remotely. The main tool I used for managing video files was Media Encoder, making sure the videos worked for mobile and had a small enough file size to not overwhelm the Spark Beacons. 

**Project Tools:**
- HTML / CSS / JS
- SASS / SCSS

## Links to Files

### _Javascript links and their associated files:_

- Model Viewer

  - Link: [https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js]
  - File-name: capitolReefAR/js/model-viewer.js

- aframe

  - Link: [https://aframe.io/releases/1.0.4/aframe.min.js]
  - File-name: capitolReefAR/js/aframe.js

- aframe AR NFT

  - Link: [https://raw.githack.com/AR-js-org/AR.js/master/aframe/build/aframe-ar-nft.js]
  - File-name: capitolReefAR/js/aframe-ar-nft.js

- aframe VR
  - Link: [https://cdn.jsdelivr.net/gh/aframevr/aframe@1c2407b26c61958baa93967b5412487cd94b290b/dist/aframe-master.min.js]
  - File-name: capitolReefAR/js/aframe-vr-master.js

### _Info and image links:_

- Waterpocket Fold:
  - Link: [https://www.nps.gov/care/planyourvisit/upload/FINAL-UNIGRID-PDF-CARE_S1_Web.jpg]
  - File-name: capitolReefAR/infoAssets/FINAL-UNIGRID-PDF-CARE_S1_Web.jpg

### _Font and Icon links:_

- Material Icons

  - Link: [https://fonts.googleapis.com/icon?family=Material+Icons]
  - File-name: capitolReefAR/fonts/material-icons.css
  - _Note that material icons link also had a link in the file, which was made into a file to work remotely_
  - The line <link rel="preconnect" href="https://fonts.gstatic.com"> was removed. 
- Frutiger
  - This font was from a TIF file provided by Emily Hedrick, which I ran through [Transfonter](https://transfonter.org/) to get all the other files types
  - Used [Tom Ray's Custom Fonts](https://scalablecss.com/setup-custom-fonts-with-font-face/) for instructions how to make a font work without calling to a website
  - The NPS use the Frutiger font for their websites, and we wanted to keep the style similar to what they had.
  - _because we used a different font from the previous project, we removed the fonts that were in the previous project_

### _Links Not Made into Local Files:_

These are the files that we were unable to make into pages. We may need to at one point change some of our 3D models, and figure out a way to get the information on the website. 

- File-name: capitolReefAR/adventurers.html
    - https://skfb.ly/6WQQx
    - http://creativecommons.org/licenses/by/4.0/

- File-name: capitolReefAR/jeep.html
    - https://skfb.ly/6QUOx
    - http://creativecommons.org/licenses/by-nc/4.0/
    - https://www.uvu.edu/crfs/history.html 


