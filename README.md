# 🖼️ Bulk Image Compressor

**Compress your images. Keep your files private. Keep things simple.**

A browser-based bulk image compression tool built with **HTML, CSS, and JavaScript**.

The idea is simple: high-resolution images look great, but they can also take up a lot of space and slow down websites. This project explores how image compression can be handled **directly in the browser**, without requiring a backend image-processing service.

---

## 🚀 Demo

**Live Demo:** https://christiaan-c-cupido.github.io/Bulk-Image-Compressor/

**GitHub:** Add your repository link here

---

## 💡 Why I Built This

We've all been there.

You have a folder full of high-resolution images, and suddenly you need to:

* Reduce their file sizes
* Keep the image quality reasonable
* Process several images at once
* Download everything conveniently
* And preferably **not upload your personal files somewhere else**

That's where this project comes in.

Instead of sending images to a server for processing, the application uses the browser's capabilities to handle the compression locally.

**Your images stay in the browser during the compression workflow. 🔒**

---

## ✨ What It Does

The project focuses on three main things:

### 📁 Bulk Image Processing

Select multiple images and process them as part of the same workflow rather than compressing them one at a time.

### ⚡ Client-Side Compression

Images are processed directly in the browser using the **HTML5 Canvas API**.

No dedicated image-processing backend is required for the described workflow.

### 📦 One Convenient Download

Once multiple images have been processed, **JSZip** is used to package the resulting files into a single ZIP archive.

```text
🖼️ Image 1
🖼️ Image 2
🖼️ Image 3
🖼️ Image 4
      ↓
  Compression
      ↓
    JSZip
      ↓
📦 images.zip
```

---

## 🔐 Privacy First

One of the main ideas behind this project is **client-side processing**.

Traditional image-processing services often require files to be uploaded to a server before they can be processed.

This project takes a different approach:

```text
       USER
         │
         ▼
   Select Images
         │
         ▼
      Browser
         │
         ▼
   Canvas API
         │
         ▼
 Compressed Files
         │
         ▼
      Download
```

The compression workflow takes place within the browser rather than relying on a dedicated backend service to process the images.

> **Privacy note:** Always review the actual implementation and hosting environment when evaluating the privacy characteristics of a deployed application.

---

## 🛠️ Built With

This project keeps the technology stack intentionally simple:

* **HTML5** — Structure
* **CSS3** — Styling and layout
* **JavaScript** — Application logic
* **Canvas API** — Client-side image processing
* **JSZip** — Creating ZIP archives

No backend framework is required for the described workflow.

---

## ⚙️ How It Works

### 1️⃣ Select Your Images

The user selects the images they want to process.

JavaScript accesses the selected files through the browser's file-handling capabilities.

### 2️⃣ Process the Images

The images are loaded into the browser and processed using the **HTML5 Canvas API**.

Canvas provides the functionality required to work with the image data and produce the compressed output.

```text
Original Image
      ↓
   Canvas
      ↓
Image Processing
      ↓
Compressed Image
```

### 3️⃣ Generate the Files

The processed image data is converted into downloadable files within the browser.

### 4️⃣ Package Everything

For bulk processing, **JSZip** packages the resulting files into a single ZIP archive.

### 5️⃣ Download

The final ZIP archive can then be downloaded directly from the browser.

---

## 🌐 Built as an Embeddable Widget

Another goal of this project is to make the compressor easy to integrate into existing websites.

Rather than building it exclusively as a standalone application, the project structure is designed around an **embeddable widget**.

This makes it possible to adapt the tool for environments such as:

* WordPress Custom HTML blocks
* CMS platforms supporting custom HTML
* Existing HTML websites

The idea is to keep the widget's HTML, CSS, and JavaScript self-contained enough to be dropped into an existing page without requiring an entire standalone webpage.

---

## 🎯 What I'm Practising

This project isn't just about making an image compressor.

It's an opportunity to practise building a **real, useful browser-based tool** from start to finish.

Some of the concepts explored include:

* JavaScript application logic
* Browser file handling
* Client-side processing
* HTML5 Canvas
* Working with image data
* JavaScript libraries
* ZIP file generation
* DOM manipulation
* Asynchronous JavaScript
* Embeddable web components
* Privacy-conscious application design

---

## 🧠 What Makes This Project Interesting?

The interesting part isn't simply compressing an image.

It's understanding **what the browser can do without a backend**.

Modern browsers provide access to powerful APIs that allow developers to build surprisingly capable applications without sending everything to a server.

This project is an exploration of that idea:

> **How much can we accomplish directly in the browser?**

---

## ⭐ Project Status

🚧 **Currently in development**

This project is being built as part of my development portfolio, with a focus on practical JavaScript, browser APIs, and building useful web-based tools.

---

## 👨‍💻 About

Built as a portfolio project to explore **client-side image processing, JavaScript, browser APIs, and privacy-focused web applications**.

If you find the project interesting, feel free to ⭐ the repository!
