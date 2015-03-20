react-server-example
--------------------

A simple example of how to do server-side rendering with the
[React](http://facebook.github.io/react/) library so that component code can be
shared between server and browser, as well as getting fast initial page loads
and search-engine-friendly pages.

A more complex example with shared routing and data fetching can be found at
[react-server-routing-example](https://github.com/mhart/react-server-routing-example).

Example
-------

```sh
$ npm install -g react-tools
$ npm run build:watch
$ node server.js
```

Then navigate to [http://localhost:3000](http://localhost:3000) and
click on the button to see some reactive events in action.

Try viewing the page source to ensure the HTML being sent from the server is already rendered
(with checksums to determine whether client-side rendering is necessary)
