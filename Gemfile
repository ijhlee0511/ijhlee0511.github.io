source "https://rubygems.org"

gem "jekyll", "~> 4.3"
gem "webrick"               # for `jekyll serve` on newer Rubies

# Kramdown → KaTeX math engine (server‑side render)
gem "kramdown-math-katex"   # the actual math engine plugin :contentReference[oaicite:0]{index=0}
gem "katex"                 # bundles KaTeX JS/CSS/fonts for the engine
gem "execjs"                # to run the KaTeX JS under the hood
gem "mini_racer"            # a JS runtime for ExecJS

group :jekyll_plugins do
  gem 'classifier-reborn'
  gem 'jekyll-archives'
  gem 'jekyll-diagrams'
  gem 'jekyll-email-protect'
  gem 'jekyll-feed'
  gem 'jekyll-imagemagick'
  gem 'jekyll-link-attributes'
  gem 'jekyll-minifier'
  gem 'jekyll-paginate-v2'
  gem 'jekyll-scholar'
  gem 'jekyll-sitemap'
  gem 'jekyll-toc'
  gem 'jekyll-twitter-plugin'
  gem 'jemoji'
  # …any others you need…
end


group :other_plugins do
    gem 'feedjira'
    gem 'httparty'
end
