source 'https://rubygems.org'
group :development do
  gem "capistrano", "~> 3.8"
  # Гем, который добавляет специфические для Rails таски, такие как прогон миграций и компиляция ассетов
  gem 'capistrano-rails'
  # Гем, добавляющий возможности bundle к capistrano
  gem 'capistrano-bundler'
  # Добавление поддержки Rbenv (менеджера версий для Ruby)
  gem 'capistrano-rbenv'
  # Интеграция пумы и капистрано
  gem 'capistrano3-puma'
end

group :production do 
  # Puma - это Ruby/Rack сервер, который будет получать запросы из Nginx и направлять их в Rails, эдакое связующее звено
  gem 'puma'
end