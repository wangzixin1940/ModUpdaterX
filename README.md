# ModUpdaterX

[简体中文](README-ZH.md)

*Forked from [Zch0/ModUpdater](https://github.com/Zch0/ModUpdater)*

This is a Python script that can update Minecraft Mod with just one click. Mods can be updated from the same version or across versions, reducing players' repetitive labor.

> [!important] CurseForge
> Currently, we are unable to download CurseForge mods, and it has been added to the TODO list

> [!note] Environmental Requirements
> Requirements from the original author:
> - The development uses Python version 3.12, and other versions are not guaranteed to run
> - It is recommended to use a virtual environment
> - It is recommended to run it under Linux
> *But I don't think it's important. Although some mistakes may occur. So it's better to follow the requirements*

# Quick Start
1. Install dependencies
```shell
pip3 install -r requirements.txt
```
> [!note] Windows-Curses
> If you are running this script on Windows, you also need to install a package named "windows-curses".
> ```shell
> pip install windows-curses
> ```

2. Just run it!
```shell
python3 main.py
```
**Please pay attention to modifying the configuration file when using.**

# TODO
- [ ] Optimize the UI
- [ ] Complete the setting page
- [ ] Add the function of downloading CurseForge mods
