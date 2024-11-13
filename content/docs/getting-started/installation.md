---
title: Installation
type: docs
prev: docs/getting-started/
next: usage
---

## Installing go using MTVM

The only pre-installed plugin is go because go is needed to compile plugins you download. You might not have go installed but you can install it using MTVM of course!
You can download the latest version of go using this command:

```shell
mtvm install go latest
```

Then set it as the current go version using this command:

```shell
mtvm use go latest
```

But you can also install versions directly from the use command using the \--install flag, like this:

```shell
mtvm use go latest --install
```
