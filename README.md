# ArchLive
可能是更适合中文用户的 Arch Linux Live CD

> *使用 [Archiso](https://wiki.archlinux.org/index.php/Archiso) 构建*

------
root 账户默认密码 `archlive`

xfce 分支 - Xfce

- Firefox
- Fcitx 框架与搜狗拼音
- axel：轻量的多线程下载工具
- gedit
- vim 和 gvim
- gparted
- transmission-gtk
- ……

不定期更新镜像直接下载

- [Releases](https://github.com/Yeyongmeng29/ArchLive/releases)

# 构建

```
$ git clone -b xfce https://github.com/Yeyongmeng29/ArchLive.git
$ cd ArchLive
# pacman -S archiso
# mkdir out
# ./build.sh -v
```
脚本将提示设置 root 密码

Archiso 会自动下载所需的软件包等，并在 `out` 生成镜像
