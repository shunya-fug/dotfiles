# dotfiles

chezmoi を使ったdotfiles管理リポジトリです。

## 前提条件

### macOS

- [Homebrew](https://brew.sh/) がインストール済みであること
- chezmoi がインストール済みであること

```sh
brew install chezmoi
```

## セットアップ

```sh
chezmoi init --apply https://github.com/shunya_fug/dotfiles.git
```

## パッケージの追加

### macOS

`Brewfile` に追記して `chezmoi apply` を実行します。

```sh
chezmoi apply
```
