## False impressions on JS task runners

* People think that Grunt is a monstrous tool which can do everything
* It actually is an API for writting commands. In most cases it only delegates tasks to other tools

```javascript
module.exports = function (grunt) {
    grunt.registerTask('my-task', function () {
        console.log('It is that simple');
    });
};
```

```bash
$ grunt my-task
Running "my-task" task
It is that simple

Done, without errors.
```
