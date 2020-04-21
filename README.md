# Jekyll Template for a Personal Website

This template configured to use with GitHub Pages.

## Previously

- Install Ruby <https://www.ruby-lang.org>.
- Install Ruby gems `bundler` and `jekyll`:

  ``` shell
  gem install bundler jekyll
  ```

## Configuration

Edit this files:

- `_config.yml`: edit your personal data.
- `Gemfile`: add Jekyll plugins if you need.
- `about.html`: write something about you.

## Building

``` shell
bundler install
bundler exec jekyll build
```

## Preview

``` shell
bundler exec jekyll serve --incremental --livereload
```

## Posts adding

- Open folder `_posts` and add into her a new file by sample.
- Then remember to remove these examples.

## Tags adding

- Open folder `tags` and add into her a new folder in slug name format and put into
  her `index.html` by sample.
- Then remember to remove these examples.

## Categories adding

- Open folder `categories` and add into her a new folder in slug name format and
  put into her `index.html` by sample.
- Then remember to remove these examples.

## What's next?

Read the [Jekyll documentation](https://jekyllrb.com/docs/) and check with
[GitHub Pages documentation](https://help.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll).

## License

(CC)(0)
