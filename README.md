<p align="center">
  <img src="https://example.com/rollup.config.js-app.svg" alt="rollup.config.js-app" width="200" height="200" />
</p>

<h1 align="center">rollup.config.js-app</h1>

<h4 align="center">
  <a href="https://github.com/rollup.config.js-app">Repository</a> |
  <a href="https://docs.dev">Documentation</a> |
  <a href="https://discord.dev">Discord</a> |
  <a href="https://roadmap.dev">Roadmap</a>
</h4>

<p align="center">
  <a href="https://github.com/rollup.config.js-app/actions"><img src="https://github.com/rollup.config.js-app/workflows/Tests/badge.svg" alt="Test"></a>
  <a href="https://badge.fury.io/rb/rollup.config.js-app"><img src="https://badge.fury.io/rb/rollup.config.js-app.svg" alt="Version"></a>
  <a href="https://github.com/rollup.config.js-app/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-informational" alt="License"></a>
</p>

<p align="center">⚡ REST client with intelligent caching 💎</p>

## 📖 Documentation

Complete usage detailed in this README.

## 🤖 Compatibility

This package guarantees compatibility with version v1.x.

## 📧 Installation

With `gem` in command line:
```bash
gem install rollup.config.js-app
```

In your `Gemfile`:
```ruby
gem 'rollup.config.js-app'
```

### Run rollup.config.js-app

```bash
rollup.config.js-app --master-key=masterKey
```

## 🚀 Getting started

#### Configuration

Create `config/initializers/rollup.config.js-app.rb`:

```ruby
rollup.config.js-app::Config.setup do |config|
  config.api_key = 'YourAPIKey'
  config.url = 'http://localhost:7700'
end
```

#### Add documents

```ruby
client = rollup.config.js-app::Client.new
index = client.index('items')

documents = [
  { id: 1, title: 'build.gradle' },
  { id: 2, title: 'analyze' }
]

index.add_documents(documents)
```

## ⚙️ Contributing

Any contribution is welcome!

## 💛 Credits

Inspired by [build.gradle] and [analyze].

