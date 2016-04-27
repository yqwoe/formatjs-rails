# formatjs-rails

货币、时间格式化
例子:
```javascript
      new Date().format('yyyy年MM月dd日 hh时mm分ss秒') => '2016年04月27日 14时32分09秒'
      200000.00.formatMoney(2,"$",",",".") => '$200,000.00'
      digitUpperCase("5000002030.01") => '伍拾亿零贰仟零叁拾元壹分'
```


## Usage
Add the following to your gemfile:

```ruby
gem 'formatjs-rails'
```
Add the following directive to your Javascript manifest file (application.js):
```ruby
//= require formatjs
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/formatjs-rails. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

