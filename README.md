# LuxHealth.github.io
We enable the highest-quality US health care when and where you need it.  Check us out at [LuxHealth.com](https://www.luxhealth.com).


# Recommended Installation and Development
1. `brew install chruby and ruby-install`
2. `ruby-install [ruby_version]`
3. ```
   echo "source /opt/homebrew/opt/chruby/share/chruby/chruby.sh" >> ~/.zshrc
   echo "source /opt/homebrew/opt/chruby/share/chruby/auto.sh" >> ~/.zshrc
   echo "chruby ruby-2.7.4" >> ~/.zshrc
   ```
   DO NOT INSTALL ruby-3.0.2.  Does not work with jekyll.
4. `source ~/.zshrc`
5. `bundle update && bundle install`
6. `bundle exec jekyll serve`