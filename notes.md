# Deployment Notes

Web Servers run web applications
- accept request from clients
- send back responses to clients 

Web server are a software running on someone's machine

[client] === [web server (multiple web applications/apis)]

Dev process
 - write code
 - commit and push
 - profit (it's deployed automatically to heroku)



Steps to prepare our API for deployment to Heroku

- dynamic port
- setup a "start script" that uses `node`(not nodemon) to run server


The environment is the platform (the place/operating system/machine) where application is running







