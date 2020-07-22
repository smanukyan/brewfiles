# brewfiles
My personal collection of brewfiles - `brew` config archival/restoration.

## Prerequisites
* `brew` installed
* `brew tap Homebrew/bundle`

## Archive
```
brew bundle dump --file Brewfile-dev
```

## Restore
```
brew bundle --file Brewfile-dev
```
