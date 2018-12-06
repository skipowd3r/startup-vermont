# startup-vermont
track and visualize startup activity in Vermont

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).


## Setup

```
git clone git@github.com:BurlingtonCodeAcademy/startup-vermont.git
cd startup-vermont
npm install
```

then create a personalized `.env` file containing

```
MONGODB_URI=mongodb://localhost:27017/startup-vermont
CRUNCH_KEY=123456789
```

(but using a real, secret Crunchbase API key, of course)


## Troubleshooting

|Symptom|Solution|
|---|---|
|`Could not proxy request /test from localhost:3000 to http://localhost:5000` | run your server with `npm start` in a separate terminal window |

## Development

From the project directory, you can run:

|Command|Description|
|---|---|
| `npm start` | Runs the app in production mode.<br> Open <http://localhost:5000> to view it in the browser. This page will **not** automatically reload when edits are made. You may need to run `npm run build` after making a change. |
|`npm run dev` | Runs the app in development mode. <br> Open [http://localhost:3000](http://localhost:3000) to view it in the browser. The page will reload if you make edits. <br> You will also see any lint errors in the console. <br> You must run the server too! Launch `npm start` in a separate terminal. |
| `npm test` | Launches the test runner in the interactive watch mode.<br> See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information. |
| `npm run build` | Builds the app for production to the `build` folder.<br> It correctly bundles React in production mode and optimizes the build for the best performance. See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information. |
|`npm run eject` | don't run this! [read here](https://github.com/facebook/create-react-app/blob/master/packages/react-scripts/template/README.md#npm-run-eject) for more info |
|`npm run import` | import data from Crunchbase... work in progress |
|`npm run seed` | import data from local seed JSON file... work in progress |


## Deployment

### Add heroku remote

run `git remote add heroku https://git.heroku.com/serene-shelf-38593.git` <br>

To push changes run `git push heroku master`

### MongoDB information

Created mongolab-concave-94972 as MONGOLAB_MAUVE_URI

Use `heroku addons:docs mongolab` to view documentation

## Miscellaneous

Windows mongo path: "C:\Program Files\MongoDB\Server\4.0\bin\mongo.exe"

## Links

* Crunchbase API: https://data.crunchbase.com/docs/using-the-api