# Jekyll Environment Variables

[![Buile Status](https://travis-ci.org/iBug/jekyll-environment-variables.svg?branch=master)](https://travis-ci.org/iBug/jekyll-environment-variables)

## Installation

Use `Gemfile`

```ruby
group :jekyll_plugins do
  gem 'jekyll-environment-variables'
end
```

Then run `bundle install` and let Bundler handle it for you.

## Usage

All environment variables will be copied to `site.env` for use in Liquid templates.

```html
Working directory: {{ site.env.PWD }}
```
