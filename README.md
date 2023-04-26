# Create a cli application that scrapes the current version of the website

## TODO

- [x] Command line cheatsheet steps (setup for Node.js project)
- [] Set up a `.gitignore` with the `memes` folder
- [x] Create a folder called "memes"
- [] Access the website (send a request to the website/"fetching")
- [] Search for the 'section' in the string HTML that comes back (in the "response") from the website
- [] Search from the first 10 image sources in the 'section'
  - [] Two options
    - [] One option: `.jpg` - this is in the HTML code of the website
    - [] Another option: `<img`
  - [] Get the `src` URL strings from the `img`
- [] Add the first 10 mage URL strings to an array
- [] Loop over the first 10 image URLs and:
  - [] Create a file (name correctly) in the `memes` folder (eg. `01.jpg`, `02.jpg`, etc)
  - [] Access the image URL
  - [] In this file, store the image data that comes back (in the "response") from the website
