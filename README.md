kku1993.github.io
=================

My Website built with Jekyll.

# Testing Locally

```
bundle exec jekyll serve
```

# Update

```
bundle update github-pages
```

# Setup

## Ruby

```
sudo apt-get install ruby-full build-essential zlib1g-dev

echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc

gem install bundler

cd kku1993.github.io
bundle install
```

## Jekyll (should never need to do again)

```
cd kku1993.github.io
bundle init
bundle config set path 'vendor/bundle'
bundle add jekyll -v 3.8.5
bundle exec jekyll new --force --skip-bundle .
bundle install
```
