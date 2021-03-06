<h1 align="center">Init Ubuntu</h1>

[![Travis](https://img.shields.io/travis/XuCcc/InitUbuntu.svg?style=plastic)]()
[![Github release](https://img.shields.io/badge/release-0.1.0-green.svg)](https://github.com/XuCcc/InitUbuntu/releases/tag/0.1.0)
[![platform](https://img.shields.io/badge/platform-ubuntu-lightgrey.svg)]()

![](.images/show.png)

## Tools

Use `bash InitUbuntu.sh -h` to see support tools and help.

```bash
[update]
[source]
        apt:    http://mirrors.ustc.edu.cn/ubuntu/
        pip:    https://pypi.tuna.tsinghua.edu.cn/simple
        docker: https://docker.mirrors.ustc.edu.cn
[python]
        pip: pip2&pip3
        pyenv: Simple Python version management
        pipenv: Python Development Workflow for Humans
        ptpython: an advanced Python REPL
[java]
        jdk: Oracle JDK
        maven: A software project management and comprehension tool
[docker]
        docker-ce: 
        docker-compose: A tool for defining and running multi-container Docker applications
[shell]
        zsh:
        zsh-syntax-highlighting: Fish shell like syntax highlighting for Zsh
        autojump: shell extension to jump to frequently used directories
        tmux: terminal multiplexer
        config: zsh&tmux config of Xu
```

You can find **zsh&&tmux** profiles in `./config`

## Requires

- `git&curl` You can install them easily by `bash InitUbuntu.sh --basic`
- **zsh** theme agnoster need [powerline fonts](https://github.com/powerline/fonts)



> Submit any other useful develop tools in the issue.