# Rps-react-tf

To run offline -
1) Clone the repo
2) Extract it
3) Install NodeJs (https://nodejs.org/en/)
4) Open terminal/powershell on the window
5) Type "yarn prep" to load dependencies
6) tyoe "yarn start" to start a live server.


For Netlify deploy
1) Push the site to a git repo

2)Link site with a netlify site

3)Use build commands "yarn && mkdirp dist && browserify main.js -o dist/bundle.js" to build commands

4)Remove dist/ from publish library
