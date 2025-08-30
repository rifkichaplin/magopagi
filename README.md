# Affiliates - Free Jekyll Theme

[Live Demo](https://wowthemesnet.github.io/affiliates-jekyll-theme/) | [Docs & Download](https://bootstrapstarter.com/template-affiliates-bootstrap-jekyll/) |  [Buy me a coffee](https://www.wowthemes.net/donate/)

![jekyll-affiliates-theme](https://bootstrapstarter.com/assets/img/themes/affiliates-jekyll.jpg)


Installation:
sudo apt update -y
sudo apt upgrade -y
sudo apt install ruby-full build-essential zlib1g-dev -y

echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc

gem install jekyll bundler

jekyll new my-awesome-site
cd my-awesome-site
bundle exec jekyll serve


Error CSS:
- vim assets/css/theme.scss
- Go to line 610 and replace transition: all.3s; with transition: all 0.3s;.
- jekyll serve --watch
