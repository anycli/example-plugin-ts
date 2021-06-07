@oclif/example-plugin-ts
========================

example dxcli plugin in typescript

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/@oclif/example-plugin-ts.svg)](https://npmjs.org/package/@oclif/example-plugin-ts)
[![CircleCI](https://circleci.com/gh/oclif/example-plugin-ts/tree/master.svg?style=shield)](https://circleci.com/gh/oclif/example-plugin-ts/tree/master)
[![Appveyor CI](https://ci.appveyor.com/api/projects/status/github/oclif/example-plugin-ts?branch=master&svg=true)](https://ci.appveyor.com/project/oclif/example-plugin-ts/branch/master)
[![Downloads/week](https://img.shields.io/npm/dw/@oclif/example-plugin-ts.svg)](https://npmjs.org/package/@oclif/example-plugin-ts)
[![License](https://img.shields.io/npm/l/@oclif/example-plugin-ts.svg)](https://github.com/oclif/example-plugin-ts/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g @oclif/example-plugin-ts
$ oclif-example COMMAND
running command...
$ oclif-example (-v|--version|version)
@oclif/example-plugin-ts/1.10.6 linux-x64 node-v15.11.0
$ oclif-example --help [COMMAND]
USAGE
  $ oclif-example COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`oclif-example hello [FILE]`](#oclif-example-hello-file)

## `oclif-example hello [FILE]`

describe the command here

```
USAGE
  $ oclif-example hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ oclif-example hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/oclif/example-plugin-ts/blob/v1.10.6/src/commands/hello.ts)_
<!-- commandsstop -->
