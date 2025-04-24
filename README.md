# 📄 DemoTestapp

A modern SwiftUI-based document management application that supports document listing, creation, editing, deletion, and syncing with a remote API using Core Data. The app is designed with offline support, MVVM architecture, and real-time network monitoring.

---

## ✨ Features

- ✅ **Document Listing**
  - Displays all documents in a scrollable list.
  - Supports dark/light mode and adaptive layouts.

- ✍️ **Editing Documents**
  - Swipe-to-edit functionality using a bottom sheet editor.
  - Edits are synced to both Core Data and the remote API.

- ➕ **Create New Documents**
  - Modal view for creating new documents.
  - Supports offline creation with later syncing.

- 🗑️ **Delete Documents**
  - Swipe-to-delete functionality.
  - Handles both local and remote deletion.

- ⭐ **Mark as Favorite**
  - Toggle favorite status with persistence in Core Data and the server.

- 🔄 **Offline Support & Sync**
  - Local changes are stored and automatically synced when connectivity is restored.

- 🌐 **Network Monitoring**
  - Detects network availability and triggers background sync tasks.

- 🧪 **Unit Testing**
  - Includes tests for core logic and view models using XCTest.

---

## 🏗️ Architecture

The app follows a clean **MVVM** architecture with the following structure:
