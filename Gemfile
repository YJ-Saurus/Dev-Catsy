source "https://rubygems.org"

# GitHub Pages를 사용하는 경우 (GitHub Actions로 배포 시 이 줄 주석 처리 가능)
# gem "github-pages", group: :jekyll_plugins

# 직접 Jekyll 버전 지정 (GitHub Actions 배포에 적합)
gem "jekyll", "~> 4.3"

# 기본 테마
gem "jekyll-theme-hydejack", "~> 9.2"

gem "webrick", "~> 1.8"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
end

# Windows와 JRuby에서는 tzinfo-data 필요
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end
