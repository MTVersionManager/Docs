---
title: Usage
type: docs
prev: installation
---
## Managing versions

All of the commands in this section support the "latest" keyword, which will download the latest version of a tool. Just put "latest" where you would normally put your version number

### Install a version

You can install a specified version of a tool using this command:

```shell
mtvm install [tool] [version]
```

### Set a version

You can set a specified version as your active version using this command:

```shell
mtvm use [tool] [version]
```

### Install and set a version

You can install and set a specified version using this command:

```shell
mtvm use [tool] [version] --install
```

### Remove a version

You can remove a specified version using this command:

```shell
mtvm remove [tool] [version]
```

### List versions

You can list the versions of a specified tool you have installed using this command:

```shell
mtvm list [tool]
```

## Managing plugins

### Install a plugin

You can install a plugin using this command:

```shell
mtvm plugins install [url]
```

The above command will also tell you the name of the plugin you installed so you can use other commands.

### Remove a plugin

You can remove a plugin using this command:

```shell
mtvm plugins remove [name]
```

### Update a plugin

You can update a plugin using this command:

```shell
mtvm plugins update [name]
```

### Update all plugins

You can update all of your installed plugins using this command:

```shell
mtvm plugins update
```

### List installed plugins

You can list the names of plugins you have installed using this command:

```shell
mtvm plugins
```
