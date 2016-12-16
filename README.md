# CollageMagic

CollageMagic is command line tool that lets you create an image collage from
images retrieved on Flickr and based on keywords.

You can enter up to ten keywords. If you enter less, the programme will add up
enough keywords to have ten. If you enter more, any extra one will be disregarded.

The keyword-related images will then be combined to create an image collage that will
be saved to your chosen path.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'collage_magic'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install collage_magic

## Usage

Run the following command from the command line:

    $ be bin/collage_magic start ARGV


ARGV can be any number of keywords, so you could say:

    $ be bin/collage_magic start cat dog horse

```
    Welcome! This program will let you create an image collage from random keywords.
  You can choose up to ten keywords, and I will search images on Flickr associated to them.
  If you enter less than ten keywords, I will generate as many as I need to have ten keywords.
  If you enter more than ten, any extra one will be disregarded.

  To start, you need to:
  1) enter your Flickr API key. Please type:
     $export FLICKR_API_KEY=your_api_key
  2) give me a path where you would like to have your collage saved. Please type:
     $export COLLAGE_MAGIC_IMAGE_PATH=/your/desired/path/
```

## Tests

     Tests can be run with:

         $ be rake spec


## Development


After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/collage_magic.
