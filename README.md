# Ansible role that manages the Go language installation

[![build status](https://gitlab.com/stiron/ansible-golang/badges/master/build.svg)](https://gitlab.com/stiron/ansible-golang/commits/master)

## Requirements

This module requires Ansible 2.x version.

No other dependencies have been set.

This module is tested on Debian 9 (Stretch).

## Role variables

`go_target_version` - consists of the "go" string and the exact target version, e.g. go1.11.1

`go_target_dir` - target directory where the go tools must be extracted/installed

## Examples

	- hosts: all
		roles:
		  - {role: golang, go_target_version: go1.11.1, go_target_dir: /usr/local }

## Dependencies

None

## License

MIT

## Author

Tamas Molnar <tmolnar0831@gmail.com>
