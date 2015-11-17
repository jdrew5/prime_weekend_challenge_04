# prime_weekend_challenge_04
You will be building a message board application for this weekend.

You may pick whichever of the two databases we covered for this weekend (Mongo or PostgreSQL). 

Build your project from the ground up. Build out a server that serves back down a client side experience. The client side should load an interface where a user can type in their name and then also a message. Finally a submit button should bundle all that information and send it to the server to be written to a database. 

Once the message is sent, the Client side application should load all messages that have been posted. 

Here is where it gets tricky. You will need to host it all on Heroku. We have not talked about how to get a database onto a server. For that, we have documentation on how to do it both for Mongo and for SQL. Both have free Database hosting solutions. 

HARD MODE
Build in a route that can be accessed with '/admin'. That should serve back down a different HTML file that then points to different app.js that allows the user to delete messages (a new delete button should be loaded that is not normally seen on the regular HTML). 
