
[![Build Status](https://travis-ci.org/swcraig/oxford-dictionary.svg?branch=master)](https://travis-ci.org/swcraig/oxford-dictionary)
[![Test Coverage](https://codeclimate.com/github/swcraig/oxford-dictionary/badges/coverage.svg)](https://codeclimate.com/github/swcraig/oxford-dictionary/coverage)
[![Code Climate](https://codeclimate.com/github/swcraig/oxford-dictionary/badges/gpa.svg)](https://codeclimate.com/github/swcraig/oxford-dictionary)
# OxfordDictionary

Ruby wrapper to consume the [Oxford Dictionary](https://developer.oxforddictionaries.com/documentation) API.

## Getting Started

    $ gem install oxford_dictionary

Register for an API key at the [Oxford Dictionary API site](https://developer.oxforddictionaries.com/documentation)

Setup the client:

    client = OxfordDictionary::Client.new(app_id: 'ID', app_key: 'SECRET')
    # or ...
    client = OxfordDictionary.new(app_id: 'ID', app_key: 'SECRET')

### Examples
###### Find entry

    entry = client.entry('vapid')

## Development

After checking out the repo, run `bin/setup` to install dependencies. Running `rake` will run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.


## Contributing

Bug reports and pull requests are more than welcome!

#### Pull Requests
  - Read [this often cited resource on contributing to open source projects on GitHub](https://gun.io/blog/how-to-github-fork-branch-and-pull-request)
  - Fork the project
  - Code and commit in your own feature branch
  - Open a PR and bug me to close it!



## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
