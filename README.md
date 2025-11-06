# PhotoSweep — Smart Duplicate Photo Finder (Windows)

Find and clean duplicate or near-duplicate photos based on **visual similarity**, not just file names or hashes.

PhotoSweep analyzes image content using **perceptual hashing** (aHash, dHash, pHash) to detect real duplicates — even if edited, resized, or recompressed.

---

## ✨ Features
- 🔍 Visual similarity detection (perceptual hashing)
- 📁 Scan multiple folders & entire drives
- 🖼 Supports JPG, PNG, TIFF, WebP and more
- ⚡ Multi-threaded fast hashing + SQLite index
- 🛡 Non-destructive cleanup (Move to Quarantine + undo)
- 🎚 Adjustable match threshold to fine-tune results
- 📊 Show groups of duplicate images
- ✅ Undo-safe workflow (no accidental deletions!)

---

## 🧠 How It Works
Perceptual hashes detect similarity even when:
- Images are resized/resampled
- Quality changes (JPEG recompress)
- Small edits/crops
- Renamed or moved

> Not just duplicate **files** — duplicate **photos**.

---

## 💾 Requirements
- Windows 10 or 11  
- .NET 8 Desktop Runtime (bundled for Release builds)

---

## 📦 Download
Get the latest version →  
👉 https://github.com/yourname/photosweep/releases

---

## 🔏 Privacy Notes
- Images are processed **locally**
- No cloud uploads or scanning outside chosen folders

---

## 🧩 Roadmap
- Thumbnail preview grid ✅ *(soon)*
- “Keep Best” auto-selection rules
- HEIC + RAW support (optional Magick.NET plugin)
- ORB visual feature verification (Pro mode)
- Report export (CSV)

---

## 💙 Support Development
If PhotoSweep saves you hours of cleanup:  
👉 https://ko-fi.com/yourname

---

## 📜 License
MIT — see `LICENSE.txt`
