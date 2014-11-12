Rubyのお勉強用
=====

### 勉強した本
[Rubyによるクローラー開発技法 巡回・解析機能の実装と21の運用例](http://www.amazon.co.jp/gp/product/4797380357?ie=UTF8&camp=1207&creative=8411&creativeASIN=4797380357&linkCode=shr&tag=senyoltw-22&qid=1415776561&sr=8-1&keywords=ruby+%E3%82%AF%E3%83%AD%E3%83%BC%E3%83%A9%E3%83%BC)

### ruby2系のインストール
CentOS6ではruby 1.87がインストールされていたためデフォルトではgemが使用不可だったので2系をインストール

```bash
$ sudo yum install gcc
$ sudo yum install git

$ git clone https://github.com/sstephenson/rbenv.git ~/.rbenv
$ git clone https://github.com/sstephenson/ruby-build.git ~/.rbenv/plugins/ruby-build
 
$ echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bash_profile
$ echo 'eval "$(rbenv init -)"' >> ~/.bash_profile
 
$ source ~/.bash_profile
$ rbenv --version

$ rbenv install 2.1.4
```
参考
[rbenv を利用した Ruby 環境の構築](http://dev.classmethod.jp/server-side/language/build-ruby-environment-by-rbenv/)
[rbenv を使って ruby をインストールする(CentOS編)](http://qiita.com/inouet/items/478f4228dbbcd442bfe8)

