# Firebase Cloud Messaging Push (fcm-push) Node

A simple interface to Firebase Cloud Messaging (FCM) for Android and iOS, powered by [fcm-push](https://github.com/nandarustam/fcm-push).

It will read the payload for the following variables:

 * `to`: (required) _[String]_ Device token or topic
 * `collapseKey`: _[String]_ Collapse Key
 * `data`: _[Object]_ Data passed
 * `notification`: _[Object]_ Object with two properties `title` and `body`

It uses the environment variable `FCM_SERVER_KEY` for the _server key_ configuration.


## Install

Install from [npm](http://npmjs.org)
```
npm install --save node-red-contrib-fcm-push-node
```

## License

MIT
