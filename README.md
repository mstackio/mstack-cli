# Mstack CLI

![Mstack logo](https://avatars3.githubusercontent.com/u/61955974?s=100&v=4)

[![Build Status](https://travis-ci.com/mstackio/mstack-cli.svg?branch=master)](https://travis-ci.com/mstackio/mstack-cli)
![npm](https://img.shields.io/npm/v/mstack-cli)
![GitHub](https://img.shields.io/github/license/mstackio/mstack-cli)

The Mstack CLI is used to manage Mstack apps from the command line.

# Installation

```
npm install -g mstack-cli
```

[![NPM](https://nodei.co/npm/mstack-cli.png)](https://nodei.co/npm/mstack-cli/)

# Issues

For problems directly related to the CLI, [add an issue on GitHub](https://github.com/mstackio/mstack-cli/issues/new).

[Contributors](https://github.com/mstackio/mstack-cli/contributors)

# Commands

### Login

Login into your account

```
 mstack login
```

### Logout

Logout of your account

```
 mstack logout
```

### Register

Create account on mstack

```
mstack register
```

### List all your instances

List all of your instances

```
mstack ls - List all your instances
```

### Regions

List all available regions

```
mstack regions
```

### Create new instance

Create a new instance

```
mstack create [name]
```

### Delete instance

Delete a instance by name

```
mstack delete [name]
```

### List templates

List all available premaide templates

```
mstack list-templates
```

## Template

Retrieve the template Dockerfile

```
mstack template [template-name]
```
