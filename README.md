# 🏷️ BatchCraft Studio

<div align="center">

[![Live Demo](https://img.shields.io/badge/Live_Demo-Visit_App-00C7B7?style=for-the-badge&logo=google-chrome&logoColor=white)](https://ais-pre-437izbt4k67ix2wkjckcm3-285159751481.europe-west2.run.app)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![React 18](https://img.shields.io/badge/React_18-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Firebase](https://img.shields.io/badge/Firebase_Firestore-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com/)
[![Gemini Vision](https://img.shields.io/badge/Gemini_Vision_AI-8E75C2?style=for-the-badge&logo=google&logoColor=white)](https://ai.google.dev/)

**Professional Automated Bulk Printing & Variable Data Design Engine**

*Design a master template once, connect your dataset, and mass-generate thousands of personalized badges, certificates, ID cards, dynamic QR codes, and custom labels at scale.*

[Key Features](#-key-features) • [System Architecture](#-system-architecture) • [AI Capabilities](#-ai-design-replicator) • [Tech Stack](#-tech-stack) • [Live Preview](#-live-preview--demo)

---

</div>

## 📌 Project Overview

**BatchCraft Studio** is a browser-native vector design studio and bulk variable-data printing engine built to replace tedious, manual badge/card generation workflows. 

Traditional graphic design tools collapse when tasked with merging dynamic spreadsheets with precision multi-layer vector designs. BatchCraft Studio bridges this gap by combining the intuitive flexibility of modern canvas editors with the computational power of a client-side batch compiler, AI layout replication, and real-time cloud persistence.

---

## 🚀 Key Features

### 🎨 1. Interactive Multi-Layer Canvas Engine
- **Vector & Layer Hierarchy:** Seamlessly stack, reorder, group, and style text, photos, QR codes, 1D barcodes, geometric shapes, lines, and SVG icons.
- **Precision Transformations:** Custom sub-pixel snapping, magnetic guidelines, bounding boxes, multi-point resizing handles, and rotation pivots.
- **Dynamic Typography:** Custom font pairing engine, line-height calibration, letter tracking, alignment controls, and integrated Google Fonts.

### 📊 2. Dynamic Variable Data & Spreadsheet Compiler
- **Mustache Syntax Mapping:** Bind elements to dynamic CSV columns using standard tokens (e.g., `{{FullName}}`, `{{Role}}`, `{{TicketID}}`).
- **Bulk Photo Mapping:** Map cloud image URLs or local photo directories directly into individual card layers.
- **Dynamic QR & Barcodes:** Generate crisp vector QR codes (with custom color palettes, error correction levels, and margins) and 1D barcodes on the fly for every single row.

### 🤖 3. AI Design Replicator (Gemini Vision)
- **Instant Template Deconstruction:** Drop or paste a screenshot of any physical badge, certificate, or digital template.
- **Automated Blueprint Generation:** Multimodal AI analyzes element positions, font styles, colors, and layout hierarchies, instantly reconstructing the design as editable studio layers.

### ⚡ 4. High-Throughput Batch Output Engine
- **Client-Side ZIP Archiving:** Multi-threaded Web Worker architecture generates and zips hundreds of high-resolution image cards in seconds without server lag.
- **Print-Ready PDF Exports:** Precision multi-card pagination, CMYK-safe rendering, and vector fidelity for commercial print shops.

### ☁️ 5. Cloud Ecosystem & Local Resilience
- **Optimistic Auto-Save Queue:** Real-time debounced background synchronization with visual sync badges.
- **Firebase Firestore & Auth:** Multi-project management with Google OAuth and email authentication secured by robust Firestore security rules.

---

## 🛠️ System Architecture
