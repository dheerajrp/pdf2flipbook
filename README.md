# pdf2flipbook

Convert any PDF into a self-contained, interactive HTML flipbook — with smooth page-turning, zoom, and navigation controls.

## Installation

```bash
pip install pdf2flipbook
```

## Usage

### CLI
```bash
pdf2flipbook path/to/file.pdf --output mybook.html
```

### Programmatically

```bash
from pdf2flipbook import convert_pdf_to_flipbook
convert_pdf_to_flipbook("/home/dfordheeraj/Documents/test.pdf", "test_output.html")
```

