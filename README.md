# Developer Environment: Setup and Productivity

I'll walk you through how I set up my developer environment on a new Apple machine - so you can get coding in no time! At this time, I'll be focused on setting you up for Node/JavaScript!
___

## Getting Started

Before diving in - let's cover a few important shortcuts that greatly aid in your productivity as a developer.

### Shortcuts

1. **Spotlight Search**
  * <kbd>⌘</kbd> + <kbd>Spacebar</kbd>
  * Crucial for launching applications quickly, hit the shortcut and begin typing the name of the application you want to open - hit enter.
  * Keep in mind that this shortcut combination can be disabled or swapped - I personally have "replaced" spotlight with **Alfred** which I'll cover below.

2. **Placeholder**

### Command Line
If you're not familiar with the command line - I would highly recommend spending some time getting comfortable with it before moving forward.

*Zed Shaw, author of "[The Command Line Crash Course](http://cli.learncodethehardway.org/book/)" has this to say:*

> Why? Because if you want to learn to code, then you must learn this. Programming languages are advanced ways to control your computer with language. The command line is the baby little brother of programming languages. Learning the command line teaches you to control the computer using language. Once you get past that, you can then move on to writing code and feeling like you actually own the hunk of metal you just bought.

Here are a few learning resources, go forth and shell!

* [The Command Line Crash Course](http://cli.learncodethehardway.org/book/)
* [Treehouse - Intro to Mac OS X Command Line](http://blog.teamtreehouse.com/introduction-to-the-mac-os-x-command-line)
* [Getting to Know the Command Line](http://www.davidbaumgold.com/tutorials/command-line/)

### System Update
Before getting started with setting up your environment, you'll want to make sure your system is up-to-date.

*Note: The leading `$` symbol is convention. If you didn't know this, do yourself a favor and review/learn the command line!*

List available software updates.
```
$ sudo softwareupdate -l
```

Install all available updates.
```
$ sudo software update -iva
```
### System Preferences

While some of these settings can be said to be entirely personal choice - I'd still recommend trying them out for enhancing your development experience.

Using Spotlight or Alfred ( <kbd>⌘</kbd> + <kbd>Spacebar</kbd> ), look for "system preferences" and open it up.

- Trackpad > Point & Click > `Tap to click`
- Trackpad > Scroll & Zoom > `Scroll direction: natural`
- Keyboard > Key Repeat > `Fast`
- Keyboard > Delay Until Repeat > `Short`
- Keyboard > Modifier Keys... > Caps Lock > `Control`
  - Optionally, you can use Karabiner to configure it to be <kbd>escape</kbd>
- Dock > Automatically hide and show the Dock
  - I frequently toggle this for more screen real estate using: <kbd>⌘</kbd> + <kbd>⌥</kbd> + <kbd>D</kbd>

Some users prefer to use keyboards intended for Windows machines - you'll want to go to your Keyboard settings and swap the Modifier Keys. Just follow these simple instructions to get setup:

- Keyboard > Modifier Keys... > Select Keyboard (pick the non-default keyboard)
- Your settings should then read as follows:
 * Caps Lock: Control (as previously mentioned, this is a personal preference)
 * Control: Control
 * Option: Option
 * Command: Command

Additionally, look into using a tool like Karabiner - it makes remapping keys a breeze on your machine. My personal preference is to modify the Microsoft keyboards I use on my setup, as well as mapping global keyboard repeat speeds to be even faster than what we can achieve using OSX's system settings.

- Open Karabiner > Preferences > Key Repeat (top tab):
 - Your settings should read as follows:
 * On/Off (overwrite should be toggled)
 * Parameters:
  * Delay until repeat: 250ms 
  * Key repeat: 20ms
