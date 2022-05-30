# 🗃 Permissioner

Manage permissions in a bulk manner.

## 💿 Installation

```bash
brew install ikhurramraza/tap/permissioner
```

## 📖 Usage

```
Usage: permissioner MODE DIRECTORY_PATH

ARGUMENTS:
  MODE                    Mode to be used. (Available: basic)
  DIRECTORY_PATH          Path of the directory to recursively apply permissions to.
```

## 🚀 Publishing

1. Create and push tag to GitHub.

```bash
git tag --sing -a "v[VERSION_TAG]" -m "[RELEASE_HEADER]"

git push origin "v[VERSION_TAG]"
```

2. Create a release on GitHub.

3. Update url and SHA in the Homebrew formula definition [here](https://github.com/ikhurramraza/homebrew-tap/blob/main/permissioner.rb).

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## ⚖️ License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
