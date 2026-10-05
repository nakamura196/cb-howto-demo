# frozen_string_literal: true

source 'https://rubygems.org'

# needed for Jekyll
gem 'jekyll'
gem 'webrick'
gem 'logger'
gem 'base64'
gem 'ostruct'

# needed for Rake tasks
gem 'rake'
gem 'csv'
gem 'fileutils'
gem 'mini_magick'
unless Gem.win_platform?
  gem 'image_optim'
  gem 'image_optim_pack'
end

# 日本語・中国語・韓国語の検索索引（_config.yml の cjk_index を参照）
group :jekyll_plugins do
  gem 'cjk_index', '~> 0.1.0', require: 'cjk_index/jekyll'
end
