# Sani's Homebrew Tap & APT Repository

Homebrew Tap for useful MongoDB Cloud Manager/Atlas utilities we've found valuable in day-to-day operations with MongoDB Atlas and Cloud Manager.

## Homebrew Tap

Tap the formula repository:
```plain
brew tap schabiyo/mongo
```


The following packages are provided by the APT repository:

| Package | Description | Author | Source |
| ------- | ----------- | ------ | ------ |
sherlock      | CLI tool to search through MongoDB Atlas or Cloud manager | schabiyo | [schabiyo/sherlock](https://github.com/schabiyo/sherlock)
atlas-cli   | CLI tool to interact with the Atlas API | schabiyo | [schabiyo/atlas-cli](https://github.com/mongo/atlas-cli)

To install a package from our tap, run:

`brew install schabiyo/mongo/<package>`, e.g. `brew install schabiyo/mongo/sherlock`

The above snippet will add our GPG key to your APT keychain, add the
repository, and update your cache.

