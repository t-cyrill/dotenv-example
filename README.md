# Simple dotenv example

## Usage

```
bundle install --path=vendor/bundle
bundle exec unicorn -c config/unicorn/development.rb
```

and open `localhost:3000`.

### Reload unicorn

```
kill -USR2 `cat /tmp/dotenv_example.pid`
```

