# aws-eb-config-switcher

Small utility script to manage multiple elastic beanstalk configuration
folders for the same project in a consistent and safe manner.

## Usage

```shell
$ eb-config help

usage: eb-config stash   <name>  | stash the current configuration away
usage: eb-config recover <name>  | recover a configuration by name
usage: eb-config ls              | list all stashed configurations
usage: eb-config peek            | output the full content of the configuration top level
usage: eb-config help            | show this thing
```

## License

This tool is freely available under the MIT license.
