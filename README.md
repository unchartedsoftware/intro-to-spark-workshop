# Intro to Spark Workshop

## Develop

Make sure [Node.js](https://nodejs.org/en/) is installed and global grunt `npm install -g grunt-cli`.

```shell
git clone git@github.com:unchartedsoftware/intro-to-spark-workshop.git
cd intro-to-spark-workshop
npm install
grunt serve
```

(yes default branch is `gh-pages` for simplicity)

This will open a browser window at [http://localhost:8000/#/](http://localhost:8000/#/).

Edit slides in [index.html](http://localhost:8000/#/). The `grunt serve` task watches for changes and livereloads in the browser.

Alternatively, if you don't want to use grunt, any other static server can be used such as `python -m SimpleHTTPServer` or `npm install -g http-server` and then run `http-server` from project root.

## Publish

```shell
git add .
git commit -m "description of whatever you changed"
git push
```

## reveal.js

Slides are built using the reveal.js framework. For examples of all the features possible, see [http://localhost:8000/example.html](http://localhost:8000/example.html), and [source](example.html).

Also see the reveal.js [docs](https://github.com/hakimel/reveal.js/)
