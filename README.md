# Wishlist
Serverless Website to register a wishlist that can be shared with others. Built with Vue and Firebase


TODO:
## Client side
* [ ] Create landing page
  * [ ] Add button to route to setup page
* [ ] Create wishlist setup page
  * [ ] Create Wishlist component
    * [ ] Add button to remove items 
  * [ ] Create Wishlist-item component
  * [ ] Add button to post Wishlist to firebase
* [ ] Create wishlist page
  * [ ] List all wishlist items and links
* [ ] Add router to switch between pages



## To deploy everything to the same heroku instance

* [ ] Move the server package.json to the root of the folder
* [ ] Update start script for server to be a relative path
* [ ] post-deploy script to server that will build Vue.js
* [ ] Environment variable for DB connection and token secret
* [ ] Update calls in client from localhost:5000 to be your-app.herokuapp.com
