.tmux
=====

这个是我自己使用的 tmux 配置，基于 `https://github.com/gpakosz/.tmux` 修改！感谢 [@Gregory Pakosz](https://github.com/gpakosz)


安装

1. 拉取配置信息

```
$ cd
$ git clone https://github.com/gpakosz/.tmux.git
$ ln -s -f .tmux/.tmux.conf
$ cp .tmux/.tmux.conf.local .
```

2. 安装插件

`<prefix> + I` 自动安装插件

notes: `<prefix>` 我自己使用 `C-Space`

3. 刷新配置

```
$ tmux source-file ~/.tmux.conf
```

4. 使用说明

* `<prefix> a` 打开/关闭 synchronize-panes 模式

更多详情请参考 https://github.com/gpakosz/.tmux

