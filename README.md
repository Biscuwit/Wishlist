# Wishlist
Serverless Website to register a wishlist that can be shared with others. Built with Vue and Firebase


TODO:
## Client side
* [x] Create landing page
  * [ ] Add search field to find wishlist
  * [x] Add button to route to setup page
* [x] Create wishlist setup page
  * [x] Create Wishlist component
    * [x] Add button to remove items 
  * [x] Create Wishlist-item component
  * [ ] Add button to post Wishlist to firebase
* [ ] Create wishlist page
  * [ ] List all wishlist items and links
* [x] Add router to switch between pages

## Client side styling
* [ ] Use bootstrap to style all the components


## To deploy everything to the same heroku instance

* [ ] Move the server package.json to the root of the folder
* [ ] Update start script for server to be a relative path
* [ ] post-deploy script to server that will build Vue.js
* [ ] Environment variable for DB connection and token secret
* [ ] Update calls in client from localhost:5000 to be your-app.herokuapp.com
