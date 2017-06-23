ModuleSync Configs
==================

This repository contains default configuration for
[modulesync](http://github.com/puppetlabs/modulesync) for the Lutak
puppet modules. Changes to this repository should be synced with modulesync
across all of the Lutak modules. It can also be used as an example for
creating default configuration for other community modules.

A full description of ModuleSync can be found in [ModuleSync's
README](https://github.com/puppetlabs/modulesync). This README describes how
the templates are rendered in the Puppet Labs configuration.

## Running msync

To distribute configurations from `moduleroot` to all modules, run:

```
msync update -m "Some commit description"
```

Modules will get cloned to `modules/` directory, files will be synced and
changes commited with the aforementioned comment.
