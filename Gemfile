# frozen_string_literal: true

source "https://rubygems.org"

# Chirpy 테마 엔진
gem "jekyll-theme-chirpy", "~> 7.0"

# 테스트용 (필요 없으면 삭제 가능)
gem "html-proofer", "~> 5.0", group: :test

# 필수 플러그인 그룹 (반드시 end로 닫아줘야 합니다)
group :jekyll_plugins do
  gem "jekyll-include-cache"
  gem "jekyll-archives"
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
end

# 플랫폼별 설정
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Windows 환경 보조 도구
gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]

# Ruby 3.0 이상 환경에서 로컬 실행 시 필요
gem "webrick", "~> 1.8"
