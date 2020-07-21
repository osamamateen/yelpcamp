# Yelp-Camp
A full-stack, Yelp like application for campgrounds. Built on a MongoDB/Express/Node stack, utilizing RESTful architecture with the Bootstrap 3 CSS framework for styling. The app performs CRUD operations for users, the campground and the comments. These pieces are referenced within the database through various associations. Actionable commands are displayed dynamically on the site (edit/delete) for campground and comments, depending on a user’s authorization/ownership. Flash messages handle error and success messages to provide the visitor with feedback. MongoDB Atlas, a cloud-based NoSQL database is the data store in use. User authorization and authentication in place for various routes, utilizing Passport.js and related submodules.