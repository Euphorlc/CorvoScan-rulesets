# CorvoScan Rulesets

This repository contains the official collection of rulesets used by the CorvoScan application.

## Purpose

These rules are essential for CorvoScan's diagnostics and scanning capabilities. They are managed in this central repository to allow for easy updates and version control without needing to modify the main application's code.

## Automatic Management

**This repository is not intended to be cloned manually.**

The main CorvoScan application includes a `ruleset_manager.py` module that automatically manages these files.

* **On first run:** The manager will automatically `git clone` this repository into the `/rulesets` directory of your CorvoScan project.
* **On every subsequent run:** The manager will automatically `git pull` the latest changes to ensure your rules are always up-to-date.
