# docker
To start:

`docker build -t a1-301 .`

`docker run -d --name a1-301-container -p 80:80 a1-301:latest`

`docker start a1-301-container`

To stop/remove container:

`docker stop a1-301-container`

`docker rm a1-301-container`

# heroku
`heroku login`

`heroku create --app <app-server-name>`

`heroku container:login`

`heroku container:push web --app <app-server-name>`

`heroku container:release web --app <app-server-name>`

`heroku open --app <app-server-name>`

# Write your documentation below

Write your documentation here.

#Objective Statement
To provide a web based theater blocking solution (application) for a theater
company that is user friendly, accessible, interactive/responsive, secure and
scaleable. The application will allow the directors to edit and update the
blocking for a scene and will allow the actors and other crew members view the
latest updated blocking from the director. 
