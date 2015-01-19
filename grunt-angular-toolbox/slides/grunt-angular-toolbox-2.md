```js
// tasks/collection.js
// ...
var dependencies = require('../package.json').dependencies;
for (dependency in dependencies) {
  if (dependency.indexOf('grunt-') === 0) {
    tasksDir = findup(
        path.join('node_modules', dependency, 'tasks'),
        {cwd: basepath}
    );
    if (tasksDir) {
      grunt.loadTasks(tasksDir);
    }
  }
}
// ...
```
