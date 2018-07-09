# Sample REST API repo for DevOps interview

This is a working 

## Requirements

- Node and npm
- mongodb deployment of some sort

## Installation

- Clone the repo: `git clone git@github.com:adeptmind/adept-interview-devops`
- Install dependencies: `npm install`
- Start the server: `ENV_VAR=VAL npm start`

## Configuration

```
MONGO_URI=<full URI string for mongo db server>
PORT=<port of your server>
```

## Testing the API

On a default install, triggering `npm start` will start the server on port 8080, you can then hit the `/api` route to get a hello message or the `/api/bears` route to perform RESTful operations on the `bears` resource