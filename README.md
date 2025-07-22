Deployment Instructions
To deploy the application:

Take the server file located at ./server-code/server.js and run it using:

bash
node server.js
This will work perfectly for local development.

By default, the server uses http://localhost:3000 for all database and API connections.

If you decide to deploy to a live production server, you will need to:

Update all references to localhost:3000 in your frontend pages

Replace them with your live server's domain name (e.g., https://your-live-domain.com)