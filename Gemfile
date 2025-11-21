source 'https://rubygems.org'

# Use Jekyll 4.4.x which is compatible with Ruby 3.x and tzinfo v2
gem 'jekyll', '~> 4.4.1'

# Ruby 3.x no longer ships WEBrick by default — include it for `jekyll serve`
gem 'webrick', '~> 1.8'

# tzinfo v2 is required on Ruby 3.x
gem 'tzinfo', '~> 2.0'
# On Windows platforms include tzinfo-data
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

group :jekyll_plugins do
  gem 'jekyll-feed'
  gem 'jekyll-sitemap'
  gem 'jekyll-redirect-from'
  gem 'jemoji'
end

# If you deploy via GitHub Pages and rely on the GitHub Pages build environment,
# use the `github-pages` gem instead and remove the direct `jekyll` gem above.
# The `github-pages` gem pins a set of plugins and a Jekyll version managed by GitHub.
# gem 'github-pages', group: :jekyll_plugins

