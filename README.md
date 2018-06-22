This project using to provide [CONNECT HTTP method](http://en.wikipedia.org/wiki/HTTP_tunnel#HTTP_CONNECT_Tunneling) proxy

By using [node http proxy](https://github.com/nodejitsu/node-http-proxy), inspired from [this discussion](https://github.com/nodejitsu/node-http-proxy/issues/230)


## Run the server
`npm install`  
`npm start` or `node server.js`

## Test
`node test.js`

## Deploy to heroku
Commit code to your heroku project, no configuration is required!

## Simple autentication
Set the system env variable PROXY_AUTH_KEY, and add the same value to the header 'porxy-authorization' when request the proxy header.
by default, authentication is disabled.
