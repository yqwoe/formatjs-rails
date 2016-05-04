# formatjs-rails

货币、时间格式化
例子:
```javascript
      new Date().format('yyyy年MM月dd日 hh时mm分ss秒') => '2016年04月27日 14时32分09秒'
      200000.00.formatMoney(2,"$",",",".") => '$200,000.00'
      digitUpperCase("5000002030.01") => '伍拾亿零贰仟零叁拾元壹分'
```
增加juqery导出excel
tableExport.js
jquery.base64.js


## Usage
Add the following to your gemfile:

```ruby
gem 'formatjs-rails'
```
Add the following directive to your Javascript manifest file (application.js):
```ruby
//= require formatjs
```
## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

