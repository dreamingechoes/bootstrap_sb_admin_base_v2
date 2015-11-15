[![Gem Version](https://badge.fury.io/rb/bootstrap_sb_admin_base_v2.svg)](https://badge.fury.io/rb/bootstrap_sb_admin_base_v2)

## About

bootstrap_sb_admin_base_v2 is a (work in progress) Rails gem of the Bootstrap based admin theme SB Admin 2. Originally created by Start Bootstrap, all the credits of the development of the Bootstrap admin theme are of them. This is just and adaptation into Rails gem in order to make it easier to integrate all the assets (fonts, images, css and js) into a Rails application.

You could check the original Bootstrap admin theme repository [here](https://github.com/IronSummitMedia/startbootstrap-sb-admin-2).

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'bootstrap_sb_admin_base_v2'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install bootstrap_sb_admin_base_v2

## Usage

After install the gem, the only thing you should do in your Rails application is add some lines into your manifests files. Add this into your `application.js` file:

```ruby
  //= require bootstrap_sb_admin_base_v2
```

and this line into you `application.css` file:

```ruby
  *= require bootstrap_sb_admin_base_v2
```

And you're ready to use the HTML structure of the Bootstrap based admin theme SB Admin 2 on your Rails application. All the details and documentation about this is [here](http://startbootstrap.com/template-overviews/sb-admin-2/).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/dreamingechoes/bootstrap_sb_admin_base_v2. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
