##  fine ..... but

<div class="fragment">
    <pre><code class="json">//package.json
{
    "name": "foo-collection",
    "keywords": [
        "gruntcollection"
    ],
    "dependencies": {
        "grunt-contrib-concat": "~0.5.0",
        "grunt-contrib-watch": "~0.6.1",
        "grunt-contrib-uglify": "~0.7.0",
        "grunt-karma": "~0.10.1",
        "jasmine-spec-reporter": "^1.1.1",
        "karma-chrome-launcher": "^0.1.7",
        "karma-coffee-preprocessor": "^0.2.1",
        "karma-coverage": "^0.2.7"
    }
}
</code></pre>
    <ul>
        <li>grunt also tries to load non-grunt packages</li>
        <li>no clean way to add configuration</li>
    </ul>
</div>
