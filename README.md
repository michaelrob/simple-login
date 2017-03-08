## Development Setup:

* Ruby version (2.3.0).

* Rails 5 (5.0.0.1).

* Mysql

## Setup

1. Clone git repo
2. cd into that directory.
3. I am using mysql database for development. if you are using any other update your Gemfile for corresponding database adapter.
4. Update database configurations in database.yml.

```sh
bundle install
rails db:create db:migrate db:seed
rails s
```