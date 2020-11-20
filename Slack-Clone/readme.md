# Slack-Clone
A  GraphQL Apollo Express Slack Clone with React, Babel, Nodemon, ESLint

## Road map

1. Project start


## Notes
- HTML
- CSS
- JS
- GraphQL
- Apollo
- Express
- Babel
- Nodemon
- Eslint

#Start project
to start project folder
npm init -y  

#Add dependencies
yarn add --dev nodemon babel-cli babel-preset-env babel-preset-stage-3

#Setup Babel
create .babelrc file and add
{
    "presets": [
        "env",
        "stage-3"
    ]
}

#Create a start script in package.json
  "scripts": {
    "start": "nodemon --exec babel-node index.js"
    // "test": "echo \"Error: no test specified\" && exit 1"
  },

npm start begins with  nodemon in babel-node config under index.js 


#Setup Eslint
npm install eslint --save-dev
run
npx eslint --init
choose airbnb, no react, js format

npx install-peerdeps --dev eslint-config-airbnb

#apollo
yarn add apollo-server-express express body-parser graphql graphql-tools


IMPORTANT:
For those using this in 2019 an on, you need to make sure to install "apollo-server-exress" version "^1.1.3". 
The latest version of "apollo-server-exress" will not support your code and you will receive this error message:
"TypeError: (0 , _apolloServerExpress.graphqlExpress) is not a function"

https://medium.com/@jeffrey.allen.lewis/graphql-migrating-from-apollo-server-express-1-0-to-2-0-be80f5c61bee

http://localhost:8065/graphiql

run 
{
  hi
}
see it works
