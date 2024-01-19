# bat plugin for the asdf version manager

## Dependencies

- `bash`, `curl`, `tar`.

## Install
### Plugin

```shell
asdf plugin add bat https://github.com/juli3nk/asdf-bat.git
```

### bat

```shell
# Show all installable versions
asdf list-all bat

# Install specific version
asdf install bat latest

# Set a version globally (on your ~/.tool-versions file)
asdf global bat latest

# Now bat commands are available
bat --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to install & manage versions.
