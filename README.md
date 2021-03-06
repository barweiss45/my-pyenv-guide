# my-pyenv-guide

**A Simple Guide for Installing Pyenv on MacOS, Windows, and Linux**

## Introduction
Managing multiple versions of Python on your machine can be tricky, especially when you need to test your Python against a specific code or when a particular script requires or recommends a specific version of Python. Pyenv gives some granular control over managing the various versions of Python in your environment. Without Pyenv, Python is installed globally to the system and when the Python binary is called it will be whatever version that is first found in the folders listed in your system $PATH. There are ways of getting around this without Pyenv, however, Pyenv provides a nice and smooth way of switching versions. Pyenv also ensures that when using pip to install packages, they are installed into the right “site_packages” folder for the specified version as well. In my opinion anything that makes life easier is worth using. Ultimately Pyenv combined with virtual environments, which we will discuss further in an upcoming blog, makes for a powerful tool to have in your Python tool belt for development.
Purpose

The purpose of this article is to provide a quick guide of how to install pyenv on MacOS, Windows, and Linux. For more information regarding how pyenv works and how especially how it uses shims in the system path to intercept a call to the Python binary then see Pyenv Github repository for a very straightforward and easy to understand explanation (See [Understanding Shims](https://github.com/pyenv/pyenv#understanding-shims)) . Also see this [blog](https://mungingdata.com/python/how-pyenv-works-shims/) for a very detailed explanation of Pyenv.

## TOC
- [Pyenv for MacOS](pyenv-for-macos.md)
- [The Windows Python Launcher](windows-python-launcher.md)
- [Pyenv for Windows](pyenv-for-windows.md)
- [Pyenv for Linux](pyenv-for-linux.md)

## A Quick Word about Pip
It worth noting that using pip is a breeze when using Pyenv. I always ran into issues with Pip installing a package into the correct version of python when I had multiple versions installed. Here you can see pip is pointing at the expected “site_packages” folders when I change versions.

![Screenshot of pip output](assets/screenshots/readme/pip.png)

---
Written by Barry Weiss

Email: [barweiss@cisco.com](mailto:barweiss@cisco.com)