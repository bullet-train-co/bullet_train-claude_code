# Bullet Train Claude Code Plugin

Claude Code plugin with development tools for [Bullet Train](https://bullettrain.co) applications.

## Installation

```bash
# Add the marketplace
/plugin marketplace add bullet-train-co/bullet_train-claude_code

# Install the plugin
/plugin install bullet-train@bullet-train-co/bullet_train-claude_code
```

## Available Skills

### `/bullet-train:link-core`

Clone `bullet_train-core` and link all gems for local development.

This skill:
1. Clones the `bullet_train-core` repository to `./local/bullet_train-core`
2. Discovers all gems in the cloned repo
3. Updates your `Gemfile` to use local paths for Bullet Train gems
4. Runs `bundle install` to link everything

Useful when you need to debug or contribute to Bullet Train core gems.

## License

MIT
