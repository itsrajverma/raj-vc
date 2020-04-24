## React-VideoCall

  
Video call to your friend without registering. 
Simply send your friend your auto-generated unique ID to make the call.  
Everytime you open a new tab, the server gives you a totally different unique ID.

### Development

```
# Install dependencies
yarn install

# Run server
yarn watch:server

# Run webpack-dev-server
yarn watch:client
```


### Deployment

**Heroku**

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/itsrajverma/raj-vc/tree/production)

**Custom**
```
# Install dependencies
yarn install

# Build front-end assets
yarn build

# Run server
yarn start
```
