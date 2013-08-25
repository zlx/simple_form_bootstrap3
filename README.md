Simple Form is a awesome plugin, Bootstrap 3 is the css framework I like best.
So the project is integration bootstrap 3 with simple_form.

## Installation

Add it to your Gemfile:

```ruby
gem 'simple_form', github: 'zlx/simple_form_bootstrap3', branch: 'rails_3'
```

Run the following command to install it:

```console
bundle install
```

Run the generator:

```console
rails generate simple_form:install --bootstrap3
```

Also, if you want to use the country select, you will need the
[country_select gem](https://rubygems.org/gems/country_select), add it to your Gemfile:

```ruby
gem 'country_select'
```

[The live example app](http://railsnight.zlxstar.me/)
[source code](https://github.com/zlx/rails-night)

