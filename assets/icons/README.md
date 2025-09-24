# Folio-TUI Icon Set

This directory contains a complete minimalist SVG icon set designed specifically for the folio-tui PDF processing tool. All icons follow a consistent design system with unified styling and accessibility features.

## Specifications

- **Format**: SVG
- **Size**: 24x24 viewBox
- **Stroke**: 2px width, currentColor
- **Fill**: None (transparent)
- **Style**: Round caps and joins
- **File Size**: ≤1KB each
- **Naming**: kebab-case
- **Accessibility**: All icons include descriptive `<title>` elements

## Complete Icon List

| Icon | Filename | Description | Category |
|------|----------|-------------|----------|
| 📝 | `annotate.svg` | Add annotations and notes to PDF | Text Tools |
| 📦 | `batch.svg` | Batch processing operations | Processing |
| 📑➕ | `bookmark-add.svg` | Add new bookmark | Bookmarks |
| 📑➖ | `bookmark-del.svg` | Delete bookmark | Bookmarks |
| 📑 | `bookmark.svg` | View bookmarks | Bookmarks |
| 📝 | `export-markdown.svg` | Export to Markdown format | File Operations |
| 🔍➡️ | `find-next.svg` | Find next search result | Search & Navigation |
| ❓ | `help.svg` | Show help information | Interface |
| 🖍️ | `highlight.svg` | Highlight text | Text Tools |
| 🔗 | `merge.svg` | Merge multiple documents | Processing |
| 🏷️ | `metadata-tag.svg` | Metadata and tagging | Processing |
| 📂 | `open.svg` | Open file or folder | File Operations |
| ⏭️ | `page-first.svg` | Go to first page | Page Navigation |
| ⏮️ | `page-last.svg` | Go to last page | Page Navigation |
| ➡️ | `page-next.svg` | Go to next page | Page Navigation |
| ⬅️ | `page-prev.svg` | Go to previous page | Page Navigation |
| 📄 | `pdf.svg` | PDF document representation | File Operations |
| 👁️ | `preview.svg` | Preview/view document | Interface |
| 🖨️ | `print.svg` | Print document | File Operations |
| 📏 | `range.svg` | Page range selection | Processing |
| 🔄 | `rotate.svg` | Rotate page view | Interface |
| 💾 | `save.svg` | Save document or changes | File Operations |
| 🔍 | `search.svg` | Search within document | Search & Navigation |
| ⚙️ | `settings.svg` | Open settings/preferences | Interface |
| 📱 | `split-view.svg` | Toggle split view mode | Interface |
| ✂️ | `split.svg` | Split document into parts | Processing |
| 💻 | `terminal-headless.svg` | Terminal/headless CLI mode | Interface |
| 📋 | `text-select.svg` | Select text tool | Text Tools |
| 🌞 | `theme.svg` | Change theme/appearance | Interface |
| 📑 | `toc-bookmarks.svg` | Table of contents/bookmarks | Bookmarks |
| ↩️ | `undo.svg` | Undo last operation | Interface |
| 🔍➕ | `zoom-in.svg` | Zoom in | Interface |
| 🔍➖ | `zoom-out.svg` | Zoom out | Interface |

## Usage

Each icon is a standalone SVG that can be used directly in HTML or imported into applications. The `stroke="currentColor"` attribute allows icons to inherit the text color from their parent element.

### Example Usage
```html
<svg viewBox="0 0 24 24" stroke="currentColor" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
  <title>Icon Description</title>
  <!-- Icon content -->
</svg>
```

### Integration
These icons can be used directly in terminal user interfaces that support SVG rendering, or converted to other formats as needed. The `currentColor` stroke ensures they will adapt to your application's theme automatically.

## Design Guidelines

- Icons are designed on a 24×24 pixel grid
- Consistent 2px stroke weight throughout
- Rounded line caps and joins for a friendly appearance
- Transparent backgrounds for flexibility
- Simple, recognizable metaphors for intuitive user experience
- All icons include accessibility titles for screen readers

## Categories

### File Operations
- `open.svg`, `save.svg`, `print.svg`, `pdf.svg`, `export-markdown.svg`

### Search & Navigation  
- `search.svg`, `find-next.svg`

### Page Navigation
- `page-prev.svg`, `page-next.svg`, `page-first.svg`, `page-last.svg`

### Bookmarks
- `bookmark.svg`, `bookmark-add.svg`, `bookmark-del.svg`, `toc-bookmarks.svg`

### Text Tools
- `annotate.svg`, `highlight.svg`, `text-select.svg`

### Processing
- `batch.svg`, `merge.svg`, `split.svg`, `range.svg`, `metadata-tag.svg`

### Interface
- `split-view.svg`, `theme.svg`, `settings.svg`, `help.svg`, `preview.svg`, `rotate.svg`, `zoom-in.svg`, `zoom-out.svg`, `terminal-headless.svg`, `undo.svg`