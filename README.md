# Rails 7 Starter

This is a starter app for Rails 7. It includes:

- ESBuild
- Sass
- Devise
- RSpec
- Capybara
- FactoryBot
- Faker
- Rubocop

## Getting Started

To get started, clone the repo and then install the needed gems:

```sh
$ bundle install
$ rails db:create && rails db:migrate
$ yarn install
$ EDITOR="code --wait" bin/rails credentials:edit
```

📝 we will need to set `SECRET_KEY_BASE` in the production host to the value of `secret_key_base` seen when running the `bin/rails credentials:edit` command above.

### Devise [[docs]](https://github.com/heartcombo/devise#getting-started)

```sh
$ rails generate devise:install
$ rails generate devise:views
$ rails generate devise User
```

## Tests

To run the tests:

First, install RSpec:

```sh
$ rails generate rspec:install
```

Then run tests with:

```sh
$ rspec
```
