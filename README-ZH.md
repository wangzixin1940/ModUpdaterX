# ModUpdaterX

[English](README.md)

*原作： [Zch0/ModUpdater](https://github.com/Zch0/ModUpdater)*

这是一个可以一键更新MC Mod的Python脚本。可以同版本、跨版本更新Mod，减少玩家的重复劳动。

> [!important] CurseForge
> 现在，我们还不能下载CurseForge的模组。这个功能已经被加到TODO列表。

> [!note] 环境要求
> 原作者的要求：
> - 开发用了Python 3.12，运行正常，在其他Python版本不保证正常运行
> - 最好用虚拟环境（Virtualenv、UV等）
> - 最好使用Linux
> *应该不太重要，但是我也没法保证会不会出现问题，最好还是按着要求来吧*

# 快速开始
1. 安装依赖项
```shell
pip3 install -r requirements.txt
```
> [!note] Windows-Curses
> 如果你用Windows，还需要安装"windows-curses"
> ```shell
> pip install windows-curses
> ```

2. 运行！
```shell
python3 main.py
```
**Please pay attention to modifying the configuration file when using.**

# TODO
- [ ] 优化UI
- [ ] 完成设置页面
- [ ] 增加下载CurseForge模组的功能
