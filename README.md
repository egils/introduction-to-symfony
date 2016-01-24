# Introduction to Symfony

Slides made with [reveal.js](https://github.com/hakimel/reveal.js/)

## Full setup

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install Node.js

2. Install Grunt

3. Clone the introduction-to-symfony repository

```bash
$ git clone git@github.com:egils/introduction-to-symfony.git
```

4. Navigate to the reveal.js folder

```bash
$ cd introduction-to-symfony
```

5. Install dependencies

```bash
$ npm install
```

6. Serve the presentation and monitor source files for changes

```bash
$ grunt serve
```

7. Open http://localhost:8000 to view your presentation

You can change the port by using grunt serve --port 8001.