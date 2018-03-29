# OpenStorage API Website
This stores the sources and output for https://libopenstorage.github.io. This website is created using
[gitbook](https://github.com/GitbookIO/gitbook-cli). All sources and markdown files are in the `docs` directory. The
output html created by gitbook is located in `w` directory.

## Environment setup
First, you may need to install [npm](https://nodejs.org/en/download/). Then install gitbook:

```
$ npm install -g gitbook-cli
```

To build:

```
make
```

To serve locally on `http://localhost:4000` while editing, run:

```
make serve
```

## More information
* [Gitbook](https://toolchain.gitbook.com/)
* Examples gitbook json setup
    * https://github.com/poppy-project/poppy-docs/blob/master/book.json
