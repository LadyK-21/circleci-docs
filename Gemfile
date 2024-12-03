source 'https://rubygems.org'

ruby '2.7.4'

gem "jekyll", '~> 4.2.0', github: "jekyll/jekyll"
gem 'html-proofer', '>= 3.19.3'
gem 'asciidoctor'
gem 'pygments.rb', '~> 1.1.2'
gem 'rake'
gem 'dotenv'
gem "kramdown-parser-gfm"
gem "liquid-c"
gem 'nokogiri', '~> 1.15', '>= 1.15.7'
gem 'htmlcompressor'
gem 'htmlentities', '~> 4.3', '>= 4.3.4'

group :jekyll_plugins do
  gem 'jekyll-algolia', '~> 1.0'
  gem 'jekyll-sitemap'
  gem 'jekyll-include-cache'
  gem 'jekyll-target-blank'
  gem 'jekyll-toc'
  gem 'jekyll-asciidoc', github: "asciidoctor/jekyll-asciidoc"
  gem 'jekyll-last-modified-at'
  gem 'jekyll-timeago'
  gem 'jekyll-redirect-from'
end

group :test, :development do
  gem 'pronto'
  gem 'pronto-markdownlint'
end
