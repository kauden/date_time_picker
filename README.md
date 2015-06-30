# DateTimePicker

This gem is a simple rebundling of the contents of the DateTimePicker plugin:

[DateTimePicker](http://xdsoft.net/jqplugins/datetimepicker/)

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'date_time_picker', git: 'git@gitlab.kauden.fr:ThierryCorbin/date_time_picker.git'
```

And then execute:

    $ bundle

### Add DateTimePicker to your CSS

Append the following line to your `app/assets/stylesheets/application.css` file:

    /*= require datetimepicker/datetimepicker */

If you're planning on using Sass, then you'll want to rename `application.css` to `application.scss`. That file should then look like:

    @import "datetimepicker/datetimepicker";

### Add DateTimePicker to your JS

Append the following line to your `app/assets/javascripts/application.js` file:

    //= require datetimepicker/datetimepicker

## Usage

See the website of the original project for the usage, or my original Rails3 example I point to above. This gem just saves you from having to locate and copy the javascript and stylesheet into place.

[DateTimePicker](http://xdsoft.net/jqplugins/datetimepicker/)

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request