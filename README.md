![GitHub All Releases](https://img.shields.io/github/downloads/ardittristan/HookMacros/total)
[![Donate](https://img.shields.io/badge/Donate-PayPal-Green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=TF3LJHWV9U7HN)

# VTT Hook Macros

*Advanced Scripting Module*

This module allows you to set macros to run when a particular Hook is sent by Foundry VTT.

When writing script macros, the hook arguments can be accessed via `scope.hookArgs` (or simply `hookArgs`), and user-defined arguments can be accessed by `scope.userArgs` (or simply `userArgs`).

NOTE: This fork is created to fix handling of arguments in the original repo. A pull request is created on the original repo. In the meantime this repo is used in some personal campaigns, and is not meant to be used by a wider audience.

## Installation

To install, import this [Manifest](https://raw.githubusercontent.com/ardittristan/HookMacros/master/module.json) into your module browser.

### Things to watch out for

Don't create macros that run from the chat hook *and* create chat messages that take more than 1 seconds to output to chat.

## Known non-functional hooks

* init

## Changelog

Check the [Changelog](https://github.com/ardittristan/HookMacros/blob/master/CHANGELOG.md)

---

*If you acidentally created a macro that locks you out of the game. You can fix it by holding the END key while logging into your world. This makes the module not run any macros.*
