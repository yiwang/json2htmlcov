# Convert json-cov to html-cov for mocha

### Motivation
This is a standalone npm binary to convert json-cov to html-cov for mocha, straight forward repackaged code from this [thread](https://github.com/metaskills/mocha-phantomjs/issues/10), as pointed out by [lazd](https://github.com/lazd).


### Install
    npm install -g json2htmlcov

### Usage
    $cat cov.json | json2htmlcov > cov.html

### Note
There is another useful json-cov to cobertura xml format tool: [mocha-cobertura-reporter]
(https://github.com/sjonnet19/mocha-cobertura-reporter), also using jade to render xml from json-cov.
