# Heroku
#### Heroku is a cloud platform as a service supporting several programming languages. One of the first cloud platforms, Heroku has been in development since June 2007, when it supported only the Ruby programming language, but now supports Java, Node.js, Scala, Clojure, Python, PHP, and Go.

#### Node.js is an open source, cross-platform runtime environment, which allows you to build server-side and networking applications. It's written in JavaScript and can be run within the Node.js runtime on any platform.

#### After installing Heroku and Node.js on the local machine, you need to prepare the app that you want to deploy.

#### To deploy the app, create an app on Heroku, which prepares Heroku to receive your source code:
## $ heroku create

#### When you create an app, a git remote (called heroku) is also created and associated with your local git repository.

#### Heroku generates a random name for your app, or you can pass a parameter to specify your own app name.
## $ git push heroku main

#### Now you can visit the app at the URL generated by its app name. As a handy shortcut, you can open the website as follows:
## $ heroku open

#### You can start your application locally using the heroku local command, which was installed as part of the Heroku CLI:
## $ heroku local web
