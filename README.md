html2pdf.it
===========
Using PhantomJS to generate pdfs, via a webservice. Runs using node.js.

See it in action at: [html2pdf.it](http://www.html2pdf.it).

Ready to fork and push to heroku (where I run it).

Works out of the box on both windows and linux.

On Mac you need to
```
brew install phantomjs
```

Running tests
-----------
Just type
```
npm test
````

Node modules used
----------------
- Routing etc. is done with `express`
- Testing is done with `mocha`, `chai` and `sinon`, using BBD style tests.
- JSHint is run on the JavaScript code

Node version
------------
Version 0.10+ of node.js is required (Domains are used for catching errors, and domains where not really stable before 0.10)
