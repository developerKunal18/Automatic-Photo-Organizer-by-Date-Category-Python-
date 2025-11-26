# 📸 Automatic Photo Organizer – Python Project 

## 💡 Overview
The **Automatic Photo Organizer** is a Python-based utility that scans a folder of images and automatically sorts them into organized subfolders based on:

- 📅 Date taken (from EXIF metadata)
- 🖼️ Image type (JPEG / PNG / HEIC / RAW)
- ⚠ Missing metadata (placed in `no_date`)
- 🚫 Corrupted or unreadable files (placed in `failed`)

This project works like a mini offline version of **Google Photos Auto-Organizer**, making it extremely useful for anyone with messy photo folders.

---

## 🚀 Features
- 🔍 Reads image creation date from metadata
- 📂 Automatically moves photos into monthly folders (YYYY-MM)
- 🧹 Handles corrupted/unreadable images safely
- 🎨 Supports multiple image formats
- ✨ Fully offline and private — no cloud upload required
- 💻 Works on Windows, macOS, and Linux

---

## 🧠 Concepts Used
- File automation scripts
- EXIF metadata extraction
- Path management using `pathlib`
- Error handling and fallback logic
- Working with the Pillow (`PIL`) library

---
