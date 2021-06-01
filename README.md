# Foodie Sample Gem

Welcome to my foodie gem! In this directory, you'll find the files you need to be able to package up your Ruby library into a gem.
## Build locally
- Run the command: 'bundle install --deployment'
- NB: Command requires a .gemspec manifest in the projects root
- Also run 'bundle exec rake install' to install this gem onto your local machine (requires a RakeFile in the projects root directory)
- The above command should download all dependencies into ./vendor/bundle directory

## Locate dependencies
- You can find all dependencies and their associated .gemspec manifest files in the directories below
- Dependencies : ./vendor/bundle/ruby/{version of ruby}/gems
- Manifests (.gemspec) : ./vendor/bundle/ruby/{version of ruby}/specifications

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'foodie'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install foodie

## Usage

TODO: Write usage instructions here

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/foodie. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Foodie project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/[USERNAME]/foodie/blob/master/CODE_OF_CONDUCT.md).
