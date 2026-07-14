# frozen_string_literal: true

source "https://rubygems.org"

# Chirpy 主题
gem "jekyll-theme-chirpy", "~> 7.6"

# 必需的 Jekyll 插件（就是 _config.yml 里 plugins 列表的那些）
gem "jekyll-feed", "~> 0.15"
gem "jekyll-sitemap", "~> 1.4"
gem "jekyll-paginate", "~> 1.1"
gem "jekyll-archives", "~> 2.2"
gem "jekyll-seo-tag", "~> 2.8"

# Windows 时区支持（保持不动）
platforms :windows, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Windows 文件监控（保持不动）
gem "wdm", "~> 0.2.0", platforms: [:windows]

# 本地开发测试工具（保持不动）
gem "html-proofer", "~> 5.0", group: :test
