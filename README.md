# ionic-angular2

## How to start ionic2 project

Way of making an ionic2 project is almost the same as ionic1,
except adding  ```--v2``` option when you make a new ionic2 project.

(ref: [ionicDOCS](http://ionicframework.com/docs/v2))

```
$ ionic start <project_name> --v2
```

At this time, you don't need to pre-make a project folder.

With the command, ionic2 makes a new project folder, and installs all npm modules you need.

Currently, Angular2 rc4 is only supported in ionic2. Angular2 2.0.0 is rejected by ionic2.

(ref: [5558e27](https://github.com/okapie/ionic-angular2/commit/5558e27))

## How to compile and build local server

Try to run the following command.

```
$ ionic serve
```