# sweetalert2-rails

A beautiful, responsive, customizable and accessible (WAI-ARIA) replacement for JavaScript's popup boxes. Zero dependencies.
https://limonte.github.io/sweetalert2/

This gem will override the rails default confirm dialog with SweetAlert2.

![Alt text](/screenshot.png?raw=true "Screenshot of Alert")

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'sweetalert2-rails'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install sweetalert2-rails

## Usage

Add the following to your application.scss file.
```
@import "sweetalert2-rails";
```

Add the following to your application.js file.

```
//= require sweetalert2-rails
```

Now when you use data confirm in rails, it will use sweetalert.

```
link_to 'Delete', delete_path, data: { confirm: 'Are you sure?', text: 'Will
show up as the dialog text'}
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/carlweis/sweetalert2-rails. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

