# build-a-bot
A Vue 3 app that allows you to build a custom robot and add it to a shopping cart.

This application is the result of completing a comprehensive Vue 3 course on pluralsight.com. It concerns all the fundamentals including building a project via the Vue CLI, creating components and managing communication between them, creating routes and navigating between pages, managing state and communicating with the server via Vuex, creating custom directives, and deploying the app to production.

## How to Run
### Get and Run build-abot-server
build-abot-server serves data about the robots. It was created by the instructor of the course.
Clone the build-a-bot-server app. 
```
git clone https://github.com/jmcooper/build-a-bot-server.git
```
Change directories to build-a-bot-server and do an npm install.
```
cd build-a-bot-server
npm i
``` 
Then start the server.
```
npm start
```
You can go to localhost:8081/api/parts to view the robot data.
### Get and Run build-a-bot
Clone the build-a-bot app. 
```
git clone https://github.com/g-esco101/build-a-bot.git
```
Change directories to build-a-bot and do an npm install.
```
cd build-a-bot
npm i
``` 
Then start the app (this compiles and hot-reloads for development).
```
npm run serve
```
You can go to localhost:8080 to use the app.
## Other note worthy commands
### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
