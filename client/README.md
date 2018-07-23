# How to set up a MERN stack

1. mkdir mern_app, cd mern_app
2. run create-react-app client(setting up react front end)
3. mkdir backend, touch backend/server.js, touch backend/models/comment.js (creating backend structure)
4. npm init
5. npm add express body-parser nodemon morgan mongoose concurrently babel-cli babel-preset-es2015 babel-preset-stage-0 (to get dependecies
* Express: is what we will be using as our server framework (The E in M __E__ RN)

* Body parser: a package which helps us get the body off of network requests

* Nodemon: a package that watches our server for changes, and restarts it (for a better dev experience)

* Morgan: a logging package to make it easier to debug our network requests to this api

* Mongoose: a package that lets us interact with MongoDB in an easier way (the M in __M__ ERN)

6. Remove src/logo.svg, App.css, App.test.js and App.js

7. create  CommentList.js CommentBox.js CommentForm.js Comment.js data.js CommentBox.css in src

8. npm add react-markdown whatwg-fetch prop-types

9. npm add --dev eslint babel-eslint(airbnb eslint rules)

10. npm install — save-dev`

11. run in client folder - touch .eslintrc.json
