My Mac Setup
---
macOS setup by ansible script. 🦊

## Usage

```shell script
xcode-select --install

sudo echo '/usr/local/bin/zsh' >> /etc/shells
```

## NOTE

- [ ] Do `chmod 0600 ~/.netrc` for `rails` and `heroku accounts`
- [ ] Do `bundle config --global build.pg --with-pg-config='/Applications/Postgres.app/Contents/Versions/11/bin/pg_config'`

## TODO
- [x] More brew & cask packages
- [x] Add Mas
- [x] Install Zsh & packages
- [x] Setup dotfiles
- [ ] Sync app settings (Using mackup)
- [ ] Option to skip installing brew & cask packages
