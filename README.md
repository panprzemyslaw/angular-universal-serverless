# Progressive Web App written in Angular Universal technology for serverless environment (Angular Material included)
This repo is boilerplate of Angular Universal (serverside rendering) deployed on AWS Lambda (serverless) environment.
It is running as a **progressive web app** and includes Angular Material!

## Live demo
[Angular Universal on AWS Lambda + API Gateway](https://www.angular-universal-serverless.maciejtreder.com)

## What's inside?
* Angular Material
* Service worker
* Works offline
* Webpack
* UglifyJS
* OptimizeJS
* Sass loader


## Get Started
```sh
git clone https://github.com/maciejtreder/angular-universal-serverless.git
cd angular-universal-serverless
npm install
npm start
```

## Developement mode
* Terminal 1: ```npm run watch```
* Wait for the build to finish
* Terminal 2: ```npm run server```

## Production mode
Includes AoT
```sh
npm run build:prod
npm run server
```

## Deploy on AWS Lambda
```sh
npm run build:deploy
```

Built on top of [ng-universal-demo](https://github.com/FrozenPandaz/ng-universal-demo)
