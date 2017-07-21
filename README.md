This is a starter template for [Ionic](http://ionicframework.com/docs/) projects.

## How to use this template

*This template does not work on its own*. The shared files for each starter are found in the [ionic2-app-base repo](https://github.com/ionic-team/ionic2-app-base).

To use this template, either create a new ionic project using the ionic node.js utility, or copy the files from this repository into the [Starter App Base](https://github.com/ionic-team/ionic2-app-base).

### With the Ionic CLI:

Take the name after `ionic2-starter-`, and that is the name of the template to be used when using the `ionic start` command below:

```bash
$ sudo npm install -g ionic cordova
$ ionic start myBlank blank
```

Then, to run it, cd into `myBlank` and run:

```bash
$ ionic cordova platform add ios
$ ionic cordova run ios
```

Substitute ios for android if not on a Mac.

To Use this Project Install node Modules using Commmond "npm install"

SQLite is query based RDBMS like Storage System for Mobile Devices. You can create, read, update and delete records just like in RDBMS. If you want to store/persist serious data locally, then you can relay on SQLite. Ionic 2 doesn’t ship with this by default – we can use cordova plugin to make use of SQLite.

...bash
$ cordova plugin add cordova-sqlite-storage
...

Substitute for android if not on a Mac.
