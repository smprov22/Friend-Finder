# Friend-Finder

https://agile-mesa-30631.herokuapp.com/

Inspired by the Women's World Cup that is currently happening, I created an app to match you with your Women's US Soccer BFF.  Answer a few questions and the app will tell you your soccer BFF!

You can also click on the API and view all 10 of the possible matches.

This app has modularity in the form of separate files for server logic, storing of friends, views, and routing.  The server file sets up the server and handles all the npm packages. The two html files are for the root page and the server page, which also has the modal in it. The htmlRoutes and apiRoutes files set up the browsing routes, as well as the get/post routes.  The app logic is also in the apiRoutes file. The friends.js file stores all the information about the possible matches and their survey answers.  Once the users enter all ther data, their answers are compared to the friends in the friends.js array, and the match with the closest answers is returned in a modal.

I used JavaScript ,jQuery ,node.js, Express.js, HTML, Bootstrap, and CSS to complete the app.
