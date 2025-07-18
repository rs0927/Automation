This Python script automatically sorts files in a given directory based on their extensions into organized folders like `PDFs`, `Images`, `TextFiles`, `JSON`, and `Others`.

---

## How It Works

- The script checks each file's extension.
- Moves the file into a folder based on the type:
  - `.pdf` → `PDFs`
  - `.png`, `.jpeg`, `.jpg` → `Images`
  - `.txt` → `TextFiles`
  - `.json` → `JSON`
- Files that don't match these extensions go into an `Others` folder.

---

## 🧾 Extension Mapping

```python
extension_mapping = {
    "PDFs": [".pdf"],
    "Images": [".png", ".jpeg", ".jpg"],
    "TextFiles": [".txt"],
    "JSON": [".json"]
}
