# Tests

## Load Tests

1. Install [artillery](https://artillery.io/) from NPM/Yarn/Whatever Javascript package manager is popular this week.
1. Start an instance of the server on localhost.
1. `artillery run httpGetTest.yaml` for endpoint load tests.
1. `artillery run websocketTest.yaml` for websocket load tests.


## Chat test

This will send automated fake chat messages to your localhost instance.
Edit the messages, usernames or point to a different instance.

1. `npm install`
1. `node fakeChat.js`
