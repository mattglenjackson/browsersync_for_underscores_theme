
# Browser-Sync package installer for _s (underscores) WordPress theme.

This is updated installer for Browser-Sync package for _s (underscores) theme that updates the node-sass package to a newer version.

## Installation:
- Paste the ```bs-config.js``` and ```package.json``` file in the root of the theme folder.
- Change the ```"proxy": 'INSERT LOCAL DEV WEBSITE HERE'``` to your local development website in the ```bs-config.js``` file.
- Use ```composer install``` and ```npm install``` on the command line to install the packages.
- ```npm run watch``` to run the watcher for scss to css conversion.
- ```npm run sync``` to run the browser-sync server.

