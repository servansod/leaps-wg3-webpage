Working version of LEAPS WG3 landing page.

# Local builds
For local builds, you will need to install [Jekyll](https://jekyllrb.com/).
```
~ $ gem install bundler jekyll
~ $ git clone <this repo>
~ $ cd leaps-wg3-webpage
```
Create the following `Gemfile` in the root directory:
```
source "https://rubygems.org"
git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# add jekyll as a dependency
gem "jekyll"
```
And then:
```
~/leaps-wg3-webpage $ bundle install
~/leaps-wg3-webpage $ bundle exec jekyll serve
```
Now browse to http://localhost:4000 and voilà.
