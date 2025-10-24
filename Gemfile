# frozen_string_literal: true

source "https://rubygems.org"

# Specify Jekyll version
gem "jekyll", "~> 4.3"

# Chirpy theme
gem "jekyll-theme-chirpy", "~> 7.0", ">= 7.0.1"

group :jekyll_plugins do
  gem "jekyll-paginate"
  gem "jekyll-redirect-from"
  gem "jekyll-sitemap"
  gem "jekyll-archives"
  gem "jekyll-include-cache"  # ← CRITICAL: Needed for include_cached tag
  # Remove: gem "jekyll-seo-tag"  (if you don't want SEO)
end

group :test do
  gem "html-proofer", "~> 5.0"
end

# Platform-specific gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]