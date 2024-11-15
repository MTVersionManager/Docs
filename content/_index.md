---
title: MTVM - Multiple Tool Version Manager
toc: false
---

MTVM stands for multiple tool version manager. As the name states, it is a version manager for multiple tools. The only version manager it comes with is go, and you can learn why in the [getting started guide](docs/getting-started). It is intended to be an alternative to [asdf](https://asdf-vm.com/) written in [go](https://go.dev).

## Explore

{{< cards >}}
  {{< card link="docs" title="Documentation" icon="book-open" >}}
  {{< card link="https://github.com/MTVersionManager/mtvm" title="Source Code" icon="code" >}} <!-- markdownlint-disable MD034 -->
{{< /cards >}}

## FAQ

{{% details title="Why make this instead of just using ASDF?" %}}
It's actually a very petty reason. I don't like when people use shell as a programming language instead of a scripting language like it's intended. I just noticed that there is a work in progress go version of asdf but I kinda want to make my own thing I guess 🤷. Asdf plugins will probably still be written in shell though which I don't like.
{{% /details %}}
