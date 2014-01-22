# bootstrap3-datetimepicker-rails

This gem packages the [bootstrap-datetimepicker](https://github.com/Eonasdan/bootstrap-datetimepicker) for the Rails 3.1+ asset pipeline.

Eonasdan's fork of tarruda's [bootstrap-datetimepicker](https://github.com/tarruda/bootstrap-datetimepicker) is
actively maintained and works with [Bootstrap3](http://getbootstrap.com).

[momentjs-rails](https://github.com/derekprior/momentjs-rails) is a required dependency.

## Installation

Add this line to your application's Gemfile:

```
gem 'bootstrap3-datetimepicker-rails'
```

or

```
gem 'bootstrap3-datetimepicker-rails', :git => 'https://github.com/TrevorS/bootstrap3-datetimepicker-rails.git'
```

And then execute:

```bash
$ bundle
```

Or install it yourself as:

```bash
$ gem install bootstrap3-datetimepicker-rails
```

To start using the bootstrap-datetimepicker plugin in your rails application, enable it via the asset pipeline.

Add the following to your Javascript manifest file (`application.js`):

```js
//= require moment
//= require bootstrap-datetimepicker
```

or

```js
//= require moment
//= require bootstrap-datetimepicker.min
```

If you want to include a localization, also add:

```js
//= require moment/<locale>
//= require locales/bootstrap-datetimepicker.<locale>
```

Add the following to your stylesheet file (`application.css.scss`):

```scss
@import 'bootstrap';
@import 'bootstrap-datetimepicker';
```

## Usage

Check out the documentation at: http://eonasdan.github.io/bootstrap-datetimepicker/

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
