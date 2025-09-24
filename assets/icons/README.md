# Folio-TUI Icon Set

This directory contains a complete monochrome SVG icon set designed for the folio-tui PDF processing tool.

## Specifications

- **Format**: SVG
- **Size**: 24x24 viewBox
- **Stroke**: 2px width, currentColor
- **Fill**: None (transparent)
- **Style**: Round caps and joins
- **File Size**: ≤1KB each
- **Naming**: kebab-case

## Icon List

| Icon | Filename | Description |
|------|----------|-------------|
| 📄 | `pdf.svg` | PDF document representation |
| 📑 | `toc-bookmarks.svg` | Table of contents/bookmarks |
| ✂️ | `split.svg` | Split document into parts |
| 🔗 | `merge.svg` | Merge multiple documents |
| 🎯 | `range.svg` | Page range selection |
| 👁️ | `preview.svg` | Preview/view document |
| 📝 | `export-markdown.svg` | Export to Markdown format |
| 💻 | `terminal-headless.svg` | Terminal/headless CLI mode |
| 📦 | `batch.svg` | Batch processing operations |
| 🏷️ | `metadata-tag.svg` | Metadata and tagging |
| ↩️ | `undo.svg` | Undo last operation |
| ⚙️ | `settings.svg` | Application settings |

## Usage

Each icon is a standalone SVG that can be used directly in HTML or imported into applications. The `stroke="currentColor"` attribute allows icons to inherit the text color from their parent element.

Example usage:
```html
<svg viewBox="0 0 24 24" stroke="currentColor" fill="none" stroke-width="2">
  <!-- Icon content -->
</svg>
```

All icons include a `<title>` element for accessibility.