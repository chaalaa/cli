@chaalaa/cli
============

A simple PaaS implementation for managing and deploying different versions of projects for UAT.

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/@chaalaa/cli.svg)](https://npmjs.org/package/@chaalaa/cli)
[![Downloads/week](https://img.shields.io/npm/dw/@chaalaa/cli.svg)](https://npmjs.org/package/@chaalaa/cli)
[![License](https://img.shields.io/npm/l/@chaalaa/cli.svg)](https://github.com/chaalaa/cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g @chaalaa/cli
$ chaalaa COMMAND
running command...
$ chaalaa (-v|--version|version)
@chaalaa/cli/0.0.0 darwin-x64 node-v12.20.0
$ chaalaa --help [COMMAND]
USAGE
  $ chaalaa COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`chaalaa hello [FILE]`](#chaalaa-hello-file)
* [`chaalaa help [COMMAND]`](#chaalaa-help-command)

## `chaalaa hello [FILE]`

describe the command here

```
USAGE
  $ chaalaa hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ chaalaa hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/chaalaa/cli/blob/v0.0.0/src/commands/hello.ts)_

## `chaalaa help [COMMAND]`

display help for chaalaa

```
USAGE
  $ chaalaa help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.2/src/commands/help.ts)_
<!-- commandsstop -->
