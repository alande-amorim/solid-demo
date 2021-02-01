## What it is
This repo is a simple demo app that interects with the user's solid pod. It allows for reading and writing into the users profile.

Source: https://solidproject.org/developers/tutorials/getting-started

## Usage

1. clone
2. install
3. start the server

```sh
$ git clone https://github.com/alande-amorim/solid-demo.git
$ cd solid-demo
# with yarn:
$ yarn 
$ yarn start 
# or with npm
$ npm install
$ npm run start 
```

A webserver will start on http://localhost:1234 if port 1234 is available.
If this port is not available, parcel will leverage a different port. Check the `yarn start` output.