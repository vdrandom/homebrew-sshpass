# sshpass formula for Homebrew

Homebrew maintainers reject adding [sshpass](https://github.com/Homebrew/homebrew/pull/18332) for security reasons, but some users need this.

## Install

#### Download formula
```sh
curl -L https://github.com/vdrandom/homebrew-sshpass/raw/main/sshpass.rb -o $HOMEBREW/Library/Taps/homebrew/homebrew-core/Formula/sshpass.rb
```

#### Install sshpass from source
```sh
brew install --build-from-source sshpass
```
