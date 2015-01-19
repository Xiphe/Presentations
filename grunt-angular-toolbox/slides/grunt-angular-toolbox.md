##  [grunt angular toolbox](https://github.com/Jimdo/grunt-angular-toolbox)

…so — without any helpers:

<pre class="fragment"><code class="js">// tasks/collection.js
var grunt = require('grunt');
var findup = require('findup-sync');
var basepath = require('path').resolve(__dirname, '..');
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
// …pre-configuration here…
</code></pre>
