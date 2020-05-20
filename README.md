# WebShop - A Web App With Clojure and ClojureScript

Please clone this repo including the submodules:

    git clone --recursive git@github.com:tbsschroeder/clojure-webshop-app.git

Or if you have already cloned the project, you can use:

    git submodule init
    git submodule update

## Overview

This project combines an API service written in Clojure with an UI written in ClojureScript.

## Setup

Just run:

    docker-compose up

Afterwards you will have three services:
* `backend`, listening on [localhost:8080](http://localhost:8080/)
* `frontend`, reachable in the browser on [localhost:3449](http://localhost:3449/)
* `database`, it's a PostgresQL listenging on [localhost:5432](http://localhost:5432/); username and password are `clojure`.

If you like to play with each service on it's own, please visit the repositorys

* [Clojure Webshop Api](https://github.com/tbsschroeder/clojure-webshop-api)
* [Clojure Webshop Ui](https://github.com/tbsschroeder/clojure-webshop-ui)

## Further links

* Fullstack webshop app in clojure: [tbsschroeder: Clojure Webshop Full Stack App](https://github.com/tbsschroeder/clojure-webshop-app)
* Talk about the fullstack webshop app: [tbsschroeder: Using Clojure for Web Apps](https://github.com/tbsschroeder/using-clojure-for-web-apps) or on [GitHub Pages](https://tbsschroeder.github.io/using-clojure-for-web-apps/)
* Recording of the talk on the [CodeTalks2019 (YouTube)](https://www.youtube.com/watch?v=dzGuaO38XDw)


