# Rubocop::Intum

## Installation
  
Add this line to your application's Gemfile:

```ruby
gem 'rubocop-intum', require: false
```

And add to the top of your project's RuboCop configuration file (`.rubocop.yml`) :

  ```yml
  inherit_gem:
    rubocop-intum: rubocop.yml
  ```
example: [.rubocop.yml](/.rubocop.yml)

Recommended Gems

```ruby
gem "rubocop", ">= 1.32.0", require: false
gem "rubocop-minitest", ">= 0.21.0", require: false
gem "rubocop-performance", ">= 1.14.3", require: false
gem "rubocop-rails", ">= 2.15.2", require: false
gem "rubocop-intum", ">= 0.1.2", require: false
```
