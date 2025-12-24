# billboard-hot100-dataset

This repository provides an automated scraper and dataset generator for
Billboard Hot 100 #1 songs, designed to support rule-based game mechanics.
## Why does this exist?

In my game *Love Letter from a Pigeon*, certain rules require:
- Identifying the Billboard Hot 100 #1 song for a specific week
- Validating player input against real-world historical data
- Keeping the dataset automatically up-to-date

This repository solves that problem independently from the game codebase.

## What does it do?

- Scrapes Billboard Hot 100 #1 songs from Wikipedia
- Normalizes weekly chart ranges
- Exports structured CSV/JSON data
- Auto-updates via GitHub Actions

## Automation

The dataset is automatically updated weekly using GitHub Actions.
