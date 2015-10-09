# iCapps Translations

Import the translations from the iCapps translations portal.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'icapps-translations'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install icapps-translations

## Usage

- `translations init`: Run from your project root in order to setup the translations configuration.
- `translations import`: Run from your project root in order to import the translations into the matching _.strings_ files.

## Build gem

Start by updating the version number in the `lib/icapps/translations/version.rb` file.

Then build the gem by running the following commands:

    rake build
    rake release

## Contributing

1. Fork it ( https://github.com/[my-github-username]/icapps-translations/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
