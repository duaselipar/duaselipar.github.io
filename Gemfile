source "https://rubygems.org"

# Plugins Jekyll (ikut GitHub Pages)
gem "github-pages", group: :jekyll_plugins
gem "jekyll-admin", group: :jekyll_plugins

# Gem khas untuk dev di Windows (tak dihantar ke production/CI)
group :development do
  # Elak "polling" dan lajukan auto-regeneration di Windows
  gem "wdm", ">= 0.1.0", platforms: [:mingw, :x64_mingw, :mswin]

  # Faraday v2+ pisahkan retry middleware ke gem berasingan
  gem "faraday-retry"

  # (Pilihan) Jika anda guna Ruby 3.x dan nampak error "cannot load such file -- webrick",
  # nyalakan baris di bawah:
  # gem "webrick"
end
