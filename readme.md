--how to create a node project

=> npm init
=> install packages i.e npm i express mongoose connect-mongo express-session express-handlebars dotenv method-override moment morgan passport passport-google-oauth20

express is a web framework to create routes and stuffs like that.
mongoose is used to connect to our database create models and so on
connect-mongo which allows to store sessions in our database and if we reset the server we didnot get logged out.
express-session is used for session and cookies
express-handlebars for template engine
dotenv for config, manage environment variables in there
method-override allows to make post and put request
moment is used to format dates
morgan for logging
passport for authentication
passport-google-oauth20 is used to authenticate to/from google



--Dev dependencies
=> nodemon i.e npm i -D nodemon
=> cross-env i.e npm i -D cross-env


-- change the script to
"start": "cross-env NODE_ENV=production node app"
"dev": "cross-env NODE_ENV=development nodemon app"

now work to app.js