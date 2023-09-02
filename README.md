# Ruby on Rails Tutorial sample application

This is the sample app for the 
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*]
(https://www.railstutorial.corg/)

## Getting Started

To get started with the app, clone the repo and then install the need gems:

```
$ gem install bundler
$ bundle config set --local without 'production'
$ bundle install
```

Next migrate the database:

```
$ rails db:migrate
```

Finally run the tests:

```
$ rails test
```

If everything passes run the app:

```
$ rails server
```