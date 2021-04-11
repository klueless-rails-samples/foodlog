# Food log

These are the steps I took when I created food log using [crash course on Traversy Media](https://www.youtube.com/watch?v=B3Fbujmgo60)

# Install latest version of Rails

```bash
# Install
asdf install ruby 3.0.0

# List installed versions
asdf list

    nodejs
      14.7.0
    ruby
      2.7.1
      3.0.0

cd ~/dev/kweb

# set folder to use ruby 3
asdf local ruby 3.0.0

# gets created .tool-versions, you can view it with
cat .tool-versions
    ruby 3.0.0

ruby -v
    ruby 3.0.0p0 (2020-12-25 revision 95aff21468) [x86_64-darwin19]

gem install bundler

# I had to close my terminal and reopen before this would work
gem install rails

# create the application
rails new foodlog -d postgresql

cd foodlog

# Start the server
rails s

```

