Visualizing MBTA Data
=====================

[![mbtaviz.github.io](http://mbtaviz.github.io/media/wide-preview-collage.png)](http://mbtaviz.github.io/)

Visualizing MBTA Data is a web based interactive visualization that
provides a glimpse into the performance and behavior of Boston's subway
system.

Check it out: <http://mbtaviz.github.io>.

## Quick Start

1. Install [node.js](http://nodejs.org/)
2. Install `bower` to grab dependencies, `less` to compile style sheets and 
`http-server` to run the website

     `npm install -g bower less http-server`
 
3. Install dependencies

     `bower install`

4. Compile less css files into a single stylesheet

    `lessc --clean-css styles/main.less > styles/main.css`

5. Serve up the website

    `http-server`

6. Browse to [http://localhost:8080/](http://localhost:8080/) to see the 
visualization

## Source Code Layout

    data\                post-processed visualization data
    scripts\             JavaScript files for the visualization and the website
    styles\              less CSS stylesheets and main.css that they are compiled into
    media\               Opengraph/Twitter Card images
    bower.json           bower dependencies
    favicon.ico          map glyph favicon with animation
    handout.pdf          design and implementation notes
    ie.png               website rendered to an image for browsers without svg support
    index.html           landing page
    README.md            README file that appears on the website's github page
