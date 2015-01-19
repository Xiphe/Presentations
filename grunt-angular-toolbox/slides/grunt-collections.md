##  grunt collections

Lets have a look at [grunt/task.js](https://github.com/gruntjs/grunt/blob/d47c75543b09218be95869eed4c285d6044b538b/lib/grunt/task.js#L388-L405).

<pre class="fragment"><code class="json">//package.json
{
    "name": "foo-collection",
    "keywords": [
        "gruntcollection"
    ],
    "dependencies": {
        "grunt-contrib-concat": "~0.5.0",
        "grunt-contrib-watch": "~0.6.1",
        "grunt-contrib-uglify": "~0.7.0",
        "grunt-karma": "~0.10.1"
    }
}
</code></pre>
