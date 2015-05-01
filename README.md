# sassy_ink-rails

The unoffical [Sass port of Ink](https://github.com/faustgertz/sassy-ink), for the asset pipeline.

All credit for the Sass assets goes to [SassyInk](https://github.com/faustgertz/sassy-ink), this is just a repackaging.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'sassy_ink-rails'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install sassy_ink-rails

## Usage

Import the full library for use within your stylesheets:

```css
@import "zurb-ink"
```

Or selectively import the components you want components:

```css
@import
	"ink/settings",
	"ink/components/normalize",
	"ink/components/grid",
	"ink/components/block-grid",
  // etc
```

## Contributing

1. Fork it ( https://github.com/[my-github-username]/sassy_ink-rails/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
