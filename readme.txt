npm install flow-bin

export PATH=$PATH:./node_modules/.bin

  - to initializa and create .flowconfgi
flow init

npm install babel-cli babel-reset-flow -D

create .babelrc at the root of your project

babel options:
  babel src/math.js
  babel src/math.js -o math.browser.js
  babel src -d dist


PROJECT:

npm install babel-preset-stage-2 -d

// for stuff like spread operator

npm install parcel-bundler -D
// similar to web pack for bundling...


Add npm start script

define static/index.html
add index.js

update flowconfig to include ignore node_modules


npm install lit-html 
// it allows us to use javascript to render our UI



npm install flow-types -d
// for third party types...

flow-typed search lit-html
// Look for existing types

flow-typed create-stub lit-html 
// to create stub for flow typed


it will create a flow-typed folder with types...
now update flowconfig








