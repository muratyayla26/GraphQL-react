# GraphQL-React

I created this repo in parallel with [Traversy Media GraphQL Crash Course tutorial](https://www.youtube.com/watch?v=BcLNfwF04Kw) to comprehend concept and basic working principles of GraphQL.

[Apollo Client](https://www.apollographql.com/docs/react/) used for client-side state management.

To run application locally:
+ Clone the repo and run `npm install` in the root and client directory. 
+ Also, you need to create a [MongoDB database](https://www.mongodb.com/) and connect your cluster with app via connection string. Connection process; create a .env file in the root directory of app then create a variable named `MONGO_URI` with connection string value from MongoDB cluster dashboard.
+ Additionally, you can add following variables to .env file for configuration; `NODE_ENV = 'development'` and `PORT = 5000`.
+ Finally, run `npm start` in the root directory for node.js server and in the client directory for client-side app.
