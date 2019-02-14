# `generate_app_json`

Generates a simple `app.json` for the current heroku project.


This is a packaged version of [this gist](https://gist.github.com/ushu/129b3340c51a205157c1e2daa1da55fa).

## Installation

```sh
gem install generate_app_json
```

## Usage

```sh
$ cd /path/to/the/heroku/project
$ generate_app_json > ./app.json
```

and then update `app.json` with the relevant content.

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/ushu/generate_app_json.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
