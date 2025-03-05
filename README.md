# Personal Portfolio

[Aerial from html5up](https://html5up.net/aerial)

## Local Install

1. Install Ruby - `brew install chruby ruby-install`
2. Install the latest stable version of Ruby (supported by Jekyll) - `ruby-install ruby 3.4.1`
3. Configure paths

```bash
echo "source $(brew --prefix)/opt/chruby/share/chruby/chruby.sh" >> ~/.zshrc
echo "source $(brew --prefix)/opt/chruby/share/chruby/auto.sh" >> ~/.zshrc
echo "chruby ruby-3.4.1" >> ~/.zshrc
```

4. Test ruby install - `ruby -v`
5. Install Jekyll - `gem install jekyll`


## Local Development

`bundle install` then `bundle exec jekyll serve`
