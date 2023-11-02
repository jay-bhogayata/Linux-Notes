---
title: "🐧 Introduction Linux Shell"
date: 2023-11-01T21:42:55+05:30
draft: false
tags: ["linux", "shell"]
---



## 📚 Overview

- shell is linux command line interface it used to interact with the operating system.
- The **keyboard** ⌨️ interacts with the **bash (shell)** 🐚, which in turn communicates with the **operating system** 💻.
- **sh** is a Unix shell program.
- **bash** stands for Bourne Again SHell. It's an enhanced replacement for **sh**.
- A **terminal emulator**, such as GNOME Terminal, is used to interact with the shell.
- The **shell prompt** typically displays as `username@machinename:cwd$`. This can be customized.
- `cwd` stands for current working directory. 
- If the prompt ends with `#` instead of `$`, it indicates that you're logged in as a superuser 👑.
- superuser is a special user account used for system administration and it has elevated privileges.

## 📝 Some Basic Commands

```sh
date            # 📅 Displays the current date and time
```
```sh
cal             # 🗓️ Displays a calendar
```
```sh
df              # 💽 Reports disk space usage
```
```sh
df -h           # 💽 Reports disk space usage in human-readable format
```
```sh
free            # 💾 Displays amount of free and used memory in the system
```
```sh
free -h         # 💾 Displays memory info in human-readable format
```
```sh
man <command>   # 📖 Displays the manual page for a command 
```
```sh
exit            # 🚪 Exits the shell or your current session
```
## ℹ️ Additional Information

- Command history can be navigated using the up and down arrow keys  ⬆️⬇️ .
- `Ctrl+C` and `Ctrl+V` shortcuts for copy/paste do not work in the terminal. Use `Ctrl+Shift+C` and `Ctrl+Shift+V` instead.
- Multiple terminal sessions can run behind the GUI. These can be accessed using `Ctrl+Alt+F1` to `Ctrl+Alt+F6`.
- Switch between sessions using `Alt+F1-F6`.
- To return to your GUI session, use `Alt+F7`.