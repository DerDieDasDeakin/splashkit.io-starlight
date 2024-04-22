---
title: Install XCode Command Line Tools
sidebar:
  attrs:
    class: apple
  label: "1. Install XCode Command Line Tools"
---

In this guide, we will walk through the steps to install the necessary Applications and Tools that you will need to code in C# and C++ with SplashKit.  
We will be using the **Terminal** app, with the **zsh** shell. You can also use the **bash** shell if you prefer.

:::note[Already have SplashKit installed?]
If you have previously installed SplashKit (before 2024):

- Update SplashKit using your Terminal, with the command: `skm update`
- Then you can skip to Step [3. Install SplashKit Globally](#3-install-splashkit-globally)

:::

Now, let's get started!

To get SplashKit and other coding tools installed on macOS, follow the steps outlined below:

## 1. Install XCode Command Line Tools

**Xcode Command Line Tools** is a package of tools provided by Apple for developers to enable command-line development and building of software on macOS, using your **Terminal** app. *It includes tools you will need for installing SplashKit and coding in the next chapters.*

To install these tools, run the command below in your *Terminal* app:

```bash
xcode-select --install
```

![Gif showing Spotlight Search to open Terminal and pasting Xcode install command](/gifs/macos/setup-macos/terminal-xcode-install.gif)
<div class="caption">Image not subject to The Programmer's Field Guide <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/">CC BY-NC-ND 4.0 License</a></div>

:::tip[How do I find the Terminal on my Mac?]

1. Press ***Command*** (⌘) + ***Space bar*** to open the Spotlight Search.  
2. Start typing "Terminal".  
3. Click the **Terminal** app.

:::

**Note:** After running the command above, if you get something like this:

![A Terminal window showing message that 'Command Line Tools' are already installed](./src/assets/images/setup-macos/xcode-install.png)
<div class="caption">Image not subject to The Programmer's Field Guide <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/">CC BY-NC-ND 4.0 License</a></div>

That means you've already installed Xcode, and are ready to move to the next step!



