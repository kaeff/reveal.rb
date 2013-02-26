## reveal.rb

Presentations using reveal.js, preprocessing using rake-pipeline.

## Usage

Add your reveal.js presentations to the source dir. Append '.haml' to
the name for preprocessing.

To write out everything to the build directory:

  bundle exec rakep build

To run locally:

  bundle exec rakep server

To update reveal.js:

  git submodule update
