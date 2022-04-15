This is the Wei-Hong's homepage forked (edited) from [academicpages](https://github.com/academicpages/academicpages.github.io.git) created by [Stuart Geiger](https://github.com/staeiou) based on [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose and released under the MIT License. See LICENSE.md.

See more info at https://academicpages.github.io/

## To run locally (not on GitHub Pages, to serve on your own computer)

1. Clone the repository and made updates as detailed above
1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. build the page `bundle exec jekyll build --watch`
1. run the page in your local server `bundle exec jekyll serve` which will output a local link where you can see the webpage
