<p align="center">
  <img src="assets/cover.png" alt="JSONJet — Explore faster" width="100%">
</p>

<p align="center">
  <img src="assets/logo.png" alt="JSONJet logo" width="96">
</p>

<h1 align="center">JSONJet</h1>

<p align="center">
  <strong>Explore faster.</strong><br>
  A fast, local-first desktop data explorer for large structured and text files.
</p>

<p align="center">
  Open, navigate, inspect, search, and export data—all in one focused desktop app.
</p>

<p align="center">
  <a href="https://jsonjet.muchad.com/">Website</a>
  · <a href="https://github.com/muchad/jsonjet/releases/latest">Download</a>
  · <a href="https://ko-fi.com/muchad">Support Development</a>
</p>

<p align="center">
  <a href="https://github.com/muchad/jsonjet/releases/latest"><img src="https://img.shields.io/github/v/release/muchad/jsonjet?display_name=tag" alt="Latest release"></a>
  <img src="https://img.shields.io/badge/platforms-macOS%20%7C%20Windows%20%7C%20Linux-blue" alt="Available platforms">
</p>

## See JSONJet in Action

<p align="center">
  <img src="https://github.com/muchad/jsonjet/raw/main/assets/demo.gif" alt="JSONJet inspecting a large JSON file in Tree view" width="100%">
</p>

JSONJet is designed to help you explore large files without first rendering an entire document. Open a file, choose the view that suits your data, and get to the information you need while keeping the original file untouched.

## Features

- **Built for large files** — Progressive reading helps you start inspecting large datasets without waiting for the entire document to render.
- **One app, many formats** — Work with JSON, JSON Lines, spreadsheets, delimited data, Parquet, SQLite databases, SQL dumps, text, and logs.
- **Three useful views** — Explore nested structures in **Tree**, records in **Table**, or original text in **Raw** where supported.
- **Powerful search and navigation** — Search text, keys, and values; use regular expressions; and jump to a JSON path, row, or line where supported.
- **Inspect and validate** — Check JSON syntax and CSV structure, review file details, inspect column information, and browse schemas where supported.
- **Sort, filter, copy, and export** — Focus on relevant records and export useful data without changing the source file.
- **Multi-document workspace** — Use tabs, adjust the appearance, and access desktop conveniences such as drag and drop and update checks.
- **Local-first and read-only** — Your opened file contents stay on your device. JSONJet does not upload them to its servers, edit originals, or send file contents to an analytics service.
- **SQL is not executed** — SQL dumps and SQLite contents are inspected, not run as scripts or queries.

Feature availability can vary by file format and by Free or Pro edition.

## Supported Formats

| Data type | Supported extensions | What you can do |
|---|---|---|
| **JSON & JSON Lines** | `.json`, `.jsonl`, `.ndjson`, `.geojson`, `.har` | Explore nested data, switch views, navigate paths, validate, and export where supported. |
| **Delimited data** | `.csv`, `.tsv`, `.psv` | Inspect rows, choose delimiters, filter columns, and validate structure. |
| **Spreadsheets** | `.xlsx`, `.xls`, `.ods` | Browse workbook sheets and inspect tabular data. |
| **Parquet** | `.parquet`, `.parq`, `.pq` | Inspect columnar datasets, schemas, and row groups. |
| **SQLite** | `.sqlite`, `.db`, `.sqlite3` | Browse database tables and schema without running queries. |
| **SQL dumps** | `.sql`, `.sql.gz`, `.sql.zip` | Inspect dump structures and table data; SQL statements are not executed. |
| **Text & logs** | `.txt`, `.log`, `.err` | Read line-numbered text, search content, and inspect log levels where detected. |

## Privacy by Design

JSONJet is a desktop viewer intended for local inspection of exports, application data, logs, and database backups.

- **Files stay local.** JSONJet does not upload opened file contents to its servers.
- **Originals stay untouched.** JSONJet does not edit or overwrite the files you open. Exports are saved as separate output files.
- **No usage analytics.** JSONJet does not include app-usage telemetry. Network requests are limited to optional update checks, public product information, and Pro license operations.

An internet connection may be needed to download the app, check for updates, or activate and verify a Pro license.

## Download

Download the latest release from **[GitHub Releases](https://github.com/muchad/jsonjet/releases/latest)** and choose the package for your operating system.

| Platform | Package | Notes |
|---|---|---|
| **macOS** | Universal `.dmg` | Supports Intel and Apple Silicon Macs. |
| **Windows** | x64 `.exe` installer | Installer for 64-bit Windows. |
| **Linux** | x64 `.deb` | Package for compatible Debian-based distributions. |
| **Linux** | x64 `.AppImage` | Portable package; does not use a traditional package installation. |

For product information, feature details, and licensing, visit the [JSONJet website](https://jsonjet.muchad.com/).

## Support Development

JSONJet is built independently. If it makes working with data more comfortable, consider supporting continued development.

**[Support JSONJet on Ko-fi](https://ko-fi.com/muchad)**
