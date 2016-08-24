[![Gem Version](https://badge.fury.io/rb/bootstrap_sb_admin_base_v2.svg)](https://badge.fury.io/rb/bootstrap_sb_admin_base_v2)

## About

bootstrap_sb_admin_base_v2 is a (work in progress) Rails gem of the Bootstrap based admin theme SB Admin 2. Originally created by Start Bootstrap, all the credits of the development of the Bootstrap admin theme are of them. This is just and adaptation into Rails gem in order to make it easier to integrate all the assets (fonts, images, css and js) into a Rails application.

You can check the original Bootstrap admin theme repository [here](https://github.com/BlackrockDigital/startbootstrap-sb-admin-2).

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

### Version 0.2.x and below

After install the gem, the only thing you should do in your Rails application is add some lines into your manifests files. Add this into your `application.js` file:

```ruby
  //= require bootstrap_sb_admin_base_v2
```

and this line into you `application.css` file:

```ruby
  *= require bootstrap_sb_admin_base_v2
```

### Version 0.3.x and above

On version 0.3.x or above has been added two dependencies: `jquery-rails` and `font-awesome-rails` in order to keep updated the versions of **jQuery** and **font-awesome**, so be sure to require `jquery-rails` on your `application.js` before require the `bootstrap_sb_admin_base_v2` file like so:

```ruby
  //= require jquery
  //= require jquery_ujs
  //= require bootstrap_sb_admin_base_v2
```

and on the `application.css` file, be sure to require the `font-awesome-rails` file:

```ruby
  *= require font-awesome
  *= require bootstrap_sb_admin_base_v2
```

### RTL Version

If you need the RTL version of the template, add this line into you `application.css` instead of the previous one:

```ruby
  *= require bootstrap_sb_admin_base_v2_rtl
```

You can check the RTL version I've used to add this adaptation [here](https://github.com/dreamingechoes/sb-admin2-rtl).

And you're ready to use the HTML structure of the Bootstrap based admin theme SB Admin 2 on your Rails application. All the details and documentation about this are [here](http://startbootstrap.com/template-overviews/sb-admin-2/).

If you need an example to see how to integrate the gem into your Rails project, I've developed a simple Rails application in order to test the gem, you can check this app here: https://sensor-admin-panel-testing.herokuapp.com (test email: example@email.com, password: 123456example), and here you have the Github repo to be able to check the code: https://github.com/dreamingechoes/sensors_admin_panel.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/dreamingechoes/bootstrap_sb_admin_base_v2. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
