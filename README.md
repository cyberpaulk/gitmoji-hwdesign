# Hardware Design gitmoji List

This repository provides a custom [Gitmoji](https://github.com/carloscuesta/gitmoji-cli) JSON list tailored for hardware and verification engineers. Use this to override the default Gitmoji list without necessity of forking the source repository.

## How to Use

If you have not installed [Gitmoji](https://github.com/carloscuesta/gitmoji-cli) yet, follow the instructions from [README](https://github.com/carloscuesta/gitmoji/blob/master/README.md).

Run `gitmoji config` set your preferences. Once you see `? Set gitmojis api url`, paste URL of the raw json source from this repository.
```
? Set gitmojis api url
https://raw.githubusercontent.com/cyberpaulk/gitmoji-hwdesign/main/gitmojis.json

```
Once you have done it, execute `gitmoji update`. If you see the following message, your gitmojis are updated.
```
✔ Gitmojis fetched successfully, these are the new emojis:
```

## Emoji Description

### HDL functional changes
- 🚧  - General RTL development
- ✨  - Introduce new features
- 🐛  - Fix a bug
- 🚨  - Fix compiler / linter warnings
- ⚡️  - Timing / area optimizations
- 🔧  - Change configuration parameters / macros
- 🚑️  - Critical hotfix
- 🩹  - Upload a patch (diff)
- ⚗️  - Perform experiments
- ♻️  - Refactor code

### Verification

- ✅  - Add or update tests
- 📈  - Coverage code
- ⚖️  - Assertions

### HDL styling changes
- 💡  - Add or update comments in source code
- 📝  - Add or update documentation / comments
- 🎨  - Improve structure / format of the code
- 👥  - Add or update contributors
- 📄  - Add or update license

### Files relocation, renaming, removal
- 🔥  - Remove code or files
- 🚚  - Move or rename files

### Merges and submodules
- ⬆️  - Update submodules
- 🔀  - Merge branches
- ➕  - Add a dependency / submodule
- ➖  - Remove a dependency / submodule

### Scripts, CI/CD
- 🔨  - Add or update development scripts
- 👷  - Add or update CI build system
- 🙈  - Add or update a .gitignore file


## How to Set Default gitmoji api url

In case you want to revert the changes described above, run `gitmoji config` and paste the default url as shown below:
```
? Set gitmojis api url
https://gitmoji.dev/api/gitmojis
```
Execute `gitmoji update` to fetch the default JSON file.