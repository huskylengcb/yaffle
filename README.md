# Yaffle
Short description and motivation.

## Usage
How to use my plugin.

## Installation
Add this line to your application's Gemfile:

```ruby
gem 'yaffle', git: 'git@github.com:huskylengcb/yaffle.git'
```

And then execute:
```bash
$ bundle
```

Or install it yourself as:
```bash
$ gem install yaffle
```

## Begin

在modals/application_record.rb中添加
```
include Yaffle::ActsAsYaffle
```

modal 中添加
```
acts_as_yaffle yaffle_text_field: :attribute
```
执行
```
Modal.new.squawk("xxx")
```

## Contributing
Contribution directions go here.

## License
The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
# yaffle
