# mmb

mmb = moa mongodb backup, backup data to a dirname that generated by momentjs's date format

[![npm version](https://badge.fury.io/js/mmb.svg)](http://badge.fury.io/js/mmb)

- [中文说明](README.zh.md)

## Install

    [sudo] npm install -g mmb
    
## Usages

    mmb init

导出

    mmb
    
导入（警告，此处会覆盖数据，请谨慎操作）

    mmi 2015-08-23_23:09


## Config

when `mmb init`, this will create a mongo.config.json

- "host": 127.0.0.1
- "port": 27017
- "db": database name
- "dirname": dirname that generated by momentjs's date format,  see http://momentjs.com/docs/#/parsing/string-format/


## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## 版本历史

- v1.1.0 实现mmi，按照日期导入，感谢 @DavidCai1993
- v1.0.0 初始化版本,实现mmb导出

## 欢迎fork和反馈

- write by `i5ting` shiren1118@126.com

如有建议或意见，请在issue提问或邮件

## License

this repo is released under the [MIT
License](http://www.opensource.org/licenses/MIT).
