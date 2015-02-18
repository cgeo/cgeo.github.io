# c:geo website

If you are looking for the source code of the c:geo app, please visit https://github.com/cgeo/cgeo instead.



# How to install and run

This site uses Jekyll. In order to test it locally you need a working Ruby environment. See [this guide](https://www.ruby-lang.org/en/documentation/installation/) for how to install Ruby on your machine.

Once Ruby is working, install *bundler* for dependency management.

```
$ gem install bundler
```

Then you can `cd` into the clone of this repository and run `bundle install` to install all necessary dependencies.

Now you can compile the source and start a local webserver:

```
$ bundle exec jekyll serve
```

The site is available at `http://localhost:4000`.

As there might be changes in the dependencies and development in Jerkyll you should run `bundle update` once a while to update everything.



# Editing the FAQ

The FAQ is located in `_data/faq.yml`. As you can see this is a [YAML](http://www.yaml.org/) file. You do not need to understand the complete syntax, just keep the indentation as it is.

Each FAQ entry uses Markdown (with [kramdown](http://kramdown.gettalong.org/) extensions) for its content.
