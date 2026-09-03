# twilight ventures

twilight ventures is an independent software studio. we build tools that augment developers and analysts with better pipelines, smoother workflows, and visual auditing. suggestions always welcome.

## Lens: data file viewers for JetBrains IDEs and VS Code

Each one opens a big file in an editor tab and reads only the page on screen, so a 10 GB file opens about as fast as a small one. Nothing goes over the network. The free tier is permanent; the Pro tier (whole-file filtering and sorting, exports, full-scan stats) is a paid subscription with its own 30-day trial per plugin.

- [JSONL Lens](https://plugins.jetbrains.com/plugin/33397): JSON Lines and NDJSON files, gzipped included
- [Log Lens](https://plugins.jetbrains.com/plugin/33416): large plain, JSONL, logfmt and ANSI logs, followed as they grow
- [Parquet Lens](https://plugins.jetbrains.com/plugin/33510): Parquet, Arrow and Feather datasets
- [SQLite Lens](https://plugins.jetbrains.com/plugin/33684): read-only SQLite database viewer
- [XLSX Lens](https://plugins.jetbrains.com/plugin/33721): read-only Excel workbook viewer
- [Notebook Lens](https://plugins.jetbrains.com/plugin/33811): Jupyter notebooks rendered as documents, outputs included, no kernel needed
- [DuckDB Lens](https://plugins.jetbrains.com/plugin/33853): read-only DuckDB database viewer
- [Heap Dump Lens](https://plugins.jetbrains.com/plugin/33908): JVM heap dumps, thread dumps and GC logs

For VS Code: [JSONL Lens](https://open-vsx.org/extension/twilightventures/jsonl-lens) and [Parquet Lens](https://open-vsx.org/extension/twilightventures/parquet-lens-viewer) on Open VSX.

Family notes, issues and the license texts live in [twilightventures13/lens](https://github.com/twilightventures13/lens).

## Suggestions and bug reports

Every plugin has an issue reporter in the Help menu that shows you the full text before anything is sent. Suggestions of any size are welcome there, or as an issue on the [lens](https://github.com/twilightventures13/lens/issues) repo.
