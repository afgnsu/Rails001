# ajax-datatables-rails 功能齊全的資料列表

This Demo is showing the use of Ajax Datatables Rails.
It is accompanied with the article I wrote in [Medum][MED] introducing the use of RubyGems.


[MED]: <https://medium.com/實用的rubygems/ajax-datatables-rails-功能齊全的資料列表-98c96e9a250a>

[SOURCE]: <https://github.com/jbox-web/ajax-datatables-rails.git>

## 安裝

01. git clone https://github.com/jbox-web/ajax-datatables-rails.git

02. rvm install 2.6.6

03. ruby -v  # 2.6.6

04. rvm gemset create rails617

05. rvm use 2.6.6@rails617

06. gem install rails -v 6.1.7

07. cd demoajax

08. bundle

09. vi config/database.yml ，新增 username: 和 password: 值

10. rake db:setup

11. rails s -b 0.0.0.0

`註：經我修改，把 *.haml 改成 *.erb，增加可讀性。`

![](https://github.com/afgnsu/Rails001/blob/main/01.jpg)

![](https://github.com/afgnsu/Rails001/blob/main/02.jpg)

![](https://github.com/afgnsu/Rails001/blob/main/03.jpg)
