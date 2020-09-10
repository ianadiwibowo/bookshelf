# Bookshelf

Bookshelf is a web app to record the book you've read. Actually this is just me trying out Hanami.

## Setup

```bash
# Run tests:
% bundle exec rake

# Run the development console:
% bundle exec hanami console

# Run the development server:
% bundle exec hanami server

# Prepare (create and migrate) DB for `development` and `test` environments:
% bundle exec hanami db prepare # Development
% HANAMI_ENV=test bundle exec hanami db prepare # Test

# Generate controller, action, and view by scaffolding
bundle exec hanami generate action web books#index
bundle exec hanami generate action web books#new

# Generate model by scaffolding
bundle exec hanami generate model book

# See all available routes
bundle exec hanami routes
```

Explore Hanami [guides](https://guides.hanamirb.org/), [API docs](http://docs.hanamirb.org/1.3.3/), or jump in [chat](http://chat.hanamirb.org) for help. Enjoy! 🌸
