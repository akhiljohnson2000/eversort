# Eversort
  EverSort is a cross-platform desktop app (Mac & Windows) built with Electron + React + SQLite that helps you bring order to messy collections of photos, videos, documents, and creative files spread across multiple hard drives.

# ✨ Features
  📂 Multi-drive detection – Index and manage files from multiple external hard disks.
  
  🗓️ Timeline organization – Browse your collection by creation date.
  
  🏷️ Smart tagging – Assign tags for people, places, and categories.
  
  🖼️ Metadata extraction – Automatically pulls EXIF, video details, and document metadata.
  
  🔍 Powerful search & filters – Find files by name, date, tags, or metadata.
  
  ♻️ Duplicate detection – Detect and prevent duplicates across drives (SHA-256 hashing).
  
  📊 Flexible views – Grid, timeline, and per-person detail panel.
  
  🔄 Background monitoring – Live scanner keeps your catalog up to date.
  
  🗺️ Future roadmap – Face recognition, map view, safe deduplication workflows, and more.

# 🚀 Tech Stack
  Electron – cross-platform desktop shell
  
  React – modern UI framework
  
  SQLite (better-sqlite3) – fast and lightweight database
  
  ExifTool + Sharp – metadata & thumbnail generation
  
  Chokidar – real-time file system monitoring

# 📦 Getting Started
  git clone https://github.com/akhiljohnson2000/eversort.git
  
  cd eversort
  
  npm install
  
  npm run start
