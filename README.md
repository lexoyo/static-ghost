
This project makes it simple to have a [Ghost](http://ghost.org/) blog hosted on Github pages.

## Instructions

### Requirements

You need to have [Buster](https://github.com/axitkhurana/buster/) installed (a few easy steps).

[Fork and clone this repository](https://github.com/lexoyo/static-ghost) to your computer

### Installation

Clone and install Ghost:

```
$ npm install
```

### Use

Load your site's data and start Ghost

```
$ npm start
```

To stop Ghost and save your site data:

```
$ npm run stop
```

Publish your changes to github pages with

```
$ git add -A
$ git commit -am "your commit message"
$ git push origin gh-pages
```

