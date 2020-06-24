# Termux application

[![构建信息](https://github.com/htname/termux-app/workflows/Build/badge.svg)](https://github.com/termux/termux-app/actions)
[![测试信息](https://github.com/htname/termux-app/workflows/Unit%20tests/badge.svg)](https://github.com/termux/termux-app/actions)
[![加入Termux讨论区 https://gitter.im/termux/termux](https://badges.gitter.im/termux/termux.svg)](https://gitter.im/termux/termux)

[Termux](https://termux.com) 是一个运行在Android的一个Linux系统环境工具。

- [Termux Reddit community](https://reddit.com/r/termux)
- [Termux Wiki](https://wiki.termux.com/wiki/)
- [Termux Twitter](http://twitter.com/termux/)

请注意，此存储库用于应用程序本身（用户界面和终端仿真）。
有关可在应用程序内安装的软件包，请参见
[termux/termux-packages](https://github.com/termux/termux-packages)

## 安装

Termux:Widget 插件可以在这里下载:

- [Google Play](https://play.google.com/store/apps/details?id=com.termux)
- [F-Droid](https://f-droid.org/en/packages/com.termux/)
- [Kali Nethunter Store](https://store.nethunter.com/en/packages/com.termux/)

此外，我们为想要尝试的人提供每次提交调试版本
淘汰最新功能或测试其提取请求。可以获得此版本
从以下列出的工作流程之一运行 [Github Actions](https://github.com/htname/termux-app/actions)
页面。

所有提供的内部版本的签名密钥都不同。切换之前
安装源，则必须卸载Termux应用程序，然后
卸载所有当前安装的插件。
## 终端引用

- [XTerm control sequences](http://invisible-island.net/xterm/ctlseqs/ctlseqs.html)
- [vt100.net](http://vt100.net/)
- [Terminal codes (ANSI and terminfo equivalents)](http://wiki.bash-hackers.org/scripting/terminalcodes)

## 终端模拟器

- VTE (libvte): Terminal emulator widget for GTK+, mainly used in gnome-terminal.
  [Source](https://github.com/GNOME/vte), [Open Issues](https://bugzilla.gnome.org/buglist.cgi?quicksearch=product%3A%22vte%22+),
  and [All (including closed) issues](https://bugzilla.gnome.org/buglist.cgi?bug_status=RESOLVED&bug_status=VERIFIED&chfield=resolution&chfieldfrom=-2000d&chfieldvalue=FIXED&product=vte&resolution=FIXED).

- iTerm 2: OS X terminal application. [Source](https://github.com/gnachman/iTerm2),
  [Issues](https://gitlab.com/gnachman/iterm2/issues) and [Documentation](http://www.iterm2.com/documentation.html)
  (which includes [iTerm2 proprietary escape codes](http://www.iterm2.com/documentation-escape-codes.html)).

- Konsole: KDE terminal application. [Source](https://projects.kde.org/projects/kde/applications/konsole/repository),
  in particular [tests](https://projects.kde.org/projects/kde/applications/konsole/repository/revisions/master/show/tests),
  [Bugs](https://bugs.kde.org/buglist.cgi?bug_severity=critical&bug_severity=grave&bug_severity=major&bug_severity=crash&bug_severity=normal&bug_severity=minor&bug_status=UNCONFIRMED&bug_status=NEW&bug_status=ASSIGNED&bug_status=REOPENED&product=konsole)
  and [Wishes](https://bugs.kde.org/buglist.cgi?bug_severity=wishlist&bug_status=UNCONFIRMED&bug_status=NEW&bug_status=ASSIGNED&bug_status=REOPENED&product=konsole).

- hterm: JavaScript terminal implementation from Chromium. [Source](https://github.com/chromium/hterm),
  including [tests](https://github.com/chromium/hterm/blob/master/js/hterm_vt_tests.js),
  and [Google group](https://groups.google.com/a/chromium.org/forum/#!forum/chromium-hterm).

- xterm: The grandfather of terminal emulators.
  [Source](http://invisible-island.net/datafiles/release/xterm.tar.gz).

- Connectbot: Android SSH client. [Source](https://github.com/connectbot/connectbot)

- Android Terminal Emulator: Android terminal app which Termux terminal handling
  is based on. Inactive. [Source](https://github.com/jackpal/Android-Terminal-Emulator).
