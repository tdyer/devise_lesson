##1. Add devise to gemfile

```ruby 
# Use devise as authentication tool
gem 'devise'
```
##2. Bundle with devise included in gems, then setup basic devise:


###install devise

```
rails g devise:install
```

###create devise models (user)

```
rails g devise user
```

###create devise views (for user)

```
rails g devise:views user
```