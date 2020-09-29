## Local development workflow

0. Install dependency by running `npm install` in both project root directory and `/ui-server`.

1. Navigate to project root directory, and run `npm run dev`. This will starts the API and UI dist proxy server on port 8080.

2. Navigate to `/ui-server` directory, and run `npm start`. This will starts the UI server on port 4200.

3. Open `localhost:4200` on broswer and start dev on it. 

## Google Cloud App Engine deployment workflow

1. Navigate to `/ui-server` directory, and run `ng build`. This will build lastest UI server output to `/ui-server/dist`

2. Navigate to project root diectory, and run `gcloud app deploy`.


### Reference
https://medium.com/bb-tutorials-and-thoughts/how-to-develop-and-build-angular-app-with-nodejs-e24c40444421