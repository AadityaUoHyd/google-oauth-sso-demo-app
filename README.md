# Using OAuth 2.0 to Access Google APIs

- Google APIs use the OAuth 2.0 protocol for authentication and authorization. 
Google supports common OAuth 2.0 scenarios such as those for web server, client-side, installed, and limited-input device applications.

- Here we are using for web applications. To begin, obtain OAuth 2.0 client credentials from the Google API Console, 
and use them in application.yml file of spring-boot code. Then your client application requests an access token from the Google Authorization Server, 
extracts a token from the response, and sends the token to the Google API that you want to access. 

- For an interactive demonstration of using OAuth 2.0 with Google (including the option to use your own client credentials in application.yml file of springboot).

- Run as Springboot program.
 Hit URL: localhost:9090/ in browser and you'll be redirected by OAuth2 to Google page for credentials in order to access your resources.
