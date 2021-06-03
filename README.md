# Foodie Sample Gem

Welcome to my foodie gem! In this directory, you'll find the files you need to be able to package up your Ruby library into a gem.
## Build locally
- Clone Repo : git clone https://github.com/lewisojile/ruby-gem-sample.git
- Change directory into project root 'cd ruby-gem-sample'
- Run the command : 'bundle config set --local path 'vendor/bundle' && bundle install && bundle exec rake install'
- NB: Command requires a .gemspec manifest and Gemfile.lock in the projects root

- The above command should download all dependencies into ./vendor/bundle directory

## Locate dependencies
- You can find all dependencies and their associated .gemspec manifest files in the directories below
- Dependencies : ./vendor/bundle/ruby/{version of ruby}/gems
- Manifests (.gemspec) : ./vendor/bundle/ruby/{version of ruby}/specifications

