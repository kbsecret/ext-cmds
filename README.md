ext-cmds
========

This repository is a central resource for custom KBSecret commands.

Check out the [customization page](https://kbsecret.github.io/customization) for a quick
explanation of how custom commands work and behave.

## Contributing a new command

New commands are always welcome. If you'd like to add your own commands to this repository,
please open a Pull Request with the following structure:

```
kbsecret-your-command/
    kbsecret-your-command
    README.md
```

Where `kbsecret-your-command` is both the directory name and executable name. Don't include
a suffix like `.sh` or `.rb` - just make sure the executable bit is set and your shabang is correct.
