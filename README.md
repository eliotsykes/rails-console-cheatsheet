# Rails Console Cheatsheet

- `rails c` starts console
- `rails db` starts db client

## `*_url` & `*_path` Route Helpers

- `app.root_path` and `app.root_url`
- `app.invoice_path` and `app.invoice_url`
- `engine_name.some_path` and `engine_name.some_url`
- `show-routes`, `show-routes -G invoice`, `help show-routes` (requires [pry-rails gem](https://github.com/rweng/pry-rails))

## ActiveRecord

- `#to_sql` outputs query, e.g. `Account.where(created_at: 1.week.ago..Time.current).to_sql`
- `show-model Account` (requires [pry-rails gem](https://github.com/rweng/pry-rails))


## Pry

- Type `help`
