# poehub

Web-based interface for the data in Content.ggpk. Hosted here: [http://poehub.org/](http://poehub.org/).

dat.specification.ini comes from [OmegaK2/PyPoE](https://github.com/OmegaK2/PyPoE)

[![Build Status](https://travis-ci.org/henrikolsson/poehub.svg)](https://travis-ci.org/henrikolsson/poehub)

## Running

Change the paths in src/poehub/config.clj. Requires [elasticsearch](https://www.elastic.co/downloads/elasticsearch) and [leiningen](http://leiningen.org/).

Development:

    $ lein ring server

Build site:

    $ lein build-site

