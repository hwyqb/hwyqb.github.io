
### MacOS Getting Started
1. clone repository
```sh
cd ~
git clone https://github.com/xjfuuu/xjfuuu.github.io.git
```
2. You will need [Ruby](https://www.ruby-lang.org/en/) and [Bundler](https://bundler.io/) to use [Jekyll](https://jekyllrb.com/).
```sh
cd ~
git clone https://github.com/xjfuuu/xjfuuu.github.io.git

sudo su
gem install jekyll
gem install bundler
```
3. Installed dependencies in the `Gemfile`:
```sh
cd xjfuuu.github.io/
bundle install
```
4. Serve the website (`localhost:4000` by default):
```sh
bundle exec jekyll serve
```