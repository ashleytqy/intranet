[![Circle CI](https://circleci.com/gh/TechAtNYU/intranet/tree/master.svg?style=svg)](https://circleci.com/gh/TechAtNYU/intranet/tree/master) [![Code Climate](https://codeclimate.com/github/TechAtNYU/intranet/badges/gpa.svg)](https://codeclimate.com/github/TechAtNYU/intranet)

##Tech@NYU Intranet

### Installation

    git clone https://github.com/TechAtNYU/intranet

    cd intranet

    npm install

### Running
The application is 100% front-end and runs using the `http-server` package.

Start the HTTP server with:

    npm start

Navigate to
    localhost:3000

If you try to use `127.0.0.1:3000`, it will tell you that you are unauthorized.

### Testing
The application uses Karma + Jasmine for unit testing and by default executes using PhantomJS. Unit tests can be found in `/test/unit`.

Start the unit-test server with:

    npm test
