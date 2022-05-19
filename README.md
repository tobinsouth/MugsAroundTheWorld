# MugsAroundTheWorld
A way to track where the media lab mugs end up...

_**[mugs.media.mit.edu](mugs.media.mit.edu)**_

_Many_ mugs will be purchased by the Media Lab student committee (studcom) with two purposes. Firstly, people can reuse mugs so we stop going through so many disposable cups. However, these reusable mugs often get stolen and left at people homes or labs. Let's turn this bug into a feature. We will track where these mugs go, and home that they end up on wondeful journeys. 

The website component will have the following sections:
* `/about` — which will explain this project (and link to this repo).
* `/all` — which will show where _all_ the mugs are and have been.
* `/mug` — which will allow the user to enter their mug code to route to:
* `/mug/<code>` — where all the locations of this mug can be seen.
* `/mug/add/<code>` — where you can record a new location for this mug.

Each mug will have a QR code that routes to `mugs.media.mit.edu/mug/` which will allow people to view the pages above.


### Some development notes:
* Thinking of using [this template](https://github.com/tailwindtoolbox/Rainblur-Landing-Page) for the html using TailwindCSS and replace the wiggly image with a mug or something.
* Planning on using a lil flask router with a bunch of static pages that either show info from the database or are a form which sends to the database.
* How are we getting location information? 
* We probably need a spreadsheet backend to store this nicely. Sheets? Can we capture the form response in Flask.
* I love the idea of minting the data at extremely low cost to a blackchain (ploygon or something?) mainly just as a play thing. No sure how best to do this but it's a good learning opportunity.


Original Authors: Tobin South & Ziv Epstein 
