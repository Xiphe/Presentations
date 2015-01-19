`npm install grunt-angular-toolbox --save-dev`

<pre class="fragment"><code class="js">// Gruntfile.js
/* global module */
module.exports = function(grunt) {
  'use strict';

  grunt.initConfig({
    pkg: grunt.file.readJSON('package.json'),
    'angular-toolbox': { /* special configuration… */ }
  });

  grunt.loadNpmTasks('grunt-angular-toolbox');

  /* overwrite anything you do not like, register additional tasks */
};</code></pre>

