[![Gem Version](https://badge.fury.io/rb/rails-bootstrap-datepicker.svg)](https://badge.fury.io/rb/rails-bootstrap-datepicker)

# rails-bootstrap-datepicker
A date picker based off Twitter Bootstrap to work with the rails asset pipeline.

This is a rails wrapper for the bootstrap datepicker here: https://github.com/uxsolutions/bootstrap-datepicker

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'rails-bootstrap-datepicker'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install rails-bootstrap-datepicker

Add this line to app/assets/stylesheets/application.css

``` css
 *= require datepicker
 /* Or if using bootstrap v3: */
 *= require datepicker3
```
OR if you have application.scss, you can require like above or import using

``` scss
  @import "datepicker"
  /* Or if using bootstrap v3 */
  @import "datepicker3"
```


Add this line to app/assets/javascripts/application.js

``` javascript
//= require bootstrap-datepicker
```

## Questions? Bugs?

Use Github Issues.

