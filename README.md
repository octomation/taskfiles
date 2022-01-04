> # 🗂 Taskfiles
>
> Set of useful Taskfiles.

[![Mirror][mirror.icon]][mirror.page]

## 💡 Idea

Build and provide template-specific Taskfile to complement its Makefile.

## 🏆 Motivation

Sometimes writing a Makefile is difficult and not always possible.

## 🤼‍♂️ How to

1. [Install `maintainer` tool][maintainer].
2. Create your own Taskfile based on pieces from the `src`.
3. Add `alias run=./Taskfile`.
4. Execute the `run` command.
5. See the `dist` directory.
6. Take profit.

## 🤲 Outputs & outcomes

### Outputs

- [godownloader](https://github.com/kamilsk/godownloader/releases/tag/homebrew).
- [goimports](https://github.com/kamilsk/go-tools/releases/tag/goimports).
- [golangci-lint](https://github.com/kamilsk/golangci-lint/releases/tag/looppointer).

### Outcomes

- [🧩 Template for typical module written on Go](https://github.com/octomation/go-module).
- [🧩 Template for typical CLI tool written on Go](https://github.com/octomation/go-tool).
- [🧩 Template for typical service written on Go](https://github.com/octomation/go-service).

<p align="right">made with ❤️ for everyone</p>

![Taskfiles][social.image]

[mirror.page]:      https://bitbucket.org/kamilsk/taskfiles
[mirror.icon]:      https://img.shields.io/badge/mirror-bitbucket-blue

[maintainer]:       https://github.com/octomation/maintainer#-installation

[social.image]:     https://socialify.git.ci/octomation/taskfiles/image?description=1&font=Raleway&language=1&name=1&owner=1&pattern=Circuit%20Board&theme=Light
