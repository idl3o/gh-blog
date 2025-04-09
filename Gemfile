source "https://rubygems.org"

gem "jekyll", "~> 4.2.0"
gem "minima", "~> 2.5.1"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-seo-tag", "~> 2.7.1"
  gem "jekyll-sitemap", "~> 1.4.0"
  gem "jekyll-redirect-from", "~> 0.16.0"
  gem "jekyll-titles-from-headings", "~> 0.5.3"
  gem "jekyll-include-cache", "~> 0.2.1"
  gem 'github-pages'
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock Jekyll to v4.2 (GitHub Pages uses Jekyll 3.9, but we can build locally and deploy)
gem "webrick", "~> 1.7"

ruby -v
gem -v

echo 'export PATH="/usr/local/opt/ruby/bin:$PATH"' >> ~/.zshrc
# Or for bash: echo 'export PATH="/usr/local/opt/ruby/bin:$PATH"' >> ~/.bash_profile

gem update --system
gem install bundler
bundle update
