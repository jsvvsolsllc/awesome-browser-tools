# Awesome Browser Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Last Updated](https://img.shields.io/badge/last%20updated-2026-blue.svg)]()

> A curated list of browser-based tools that process files locally — no uploads, no servers, full privacy.

Modern browsers with WebAssembly, Canvas, and Web Workers can handle tasks that previously required desktop software or cloud services. This list collects the best tools that run entirely in your browser.

---

## Contents

- [PDF Tools](#pdf-tools)
- [Image Tools](#image-tools)
- [Video Tools](#video-tools)
- [AI Tools](#ai-tools)
- [File Tools](#file-tools)
- [Privacy Tools](#privacy-tools)
- [Related Resources](#related-resources)
- [Contributing](#contributing)

---

## PDF Tools

| Tool | Description |
|------|-------------|
| [MiOffice PDF Merge](https://mioffice.ai/tools/pdf/merge) | Merge multiple PDFs in browser, no upload. WASM-powered. |
| [MiOffice PDF Split](https://mioffice.ai/tools/pdf/split) | Split PDF into individual pages or custom ranges. Runs locally. |
| [MiOffice PDF Compress](https://mioffice.ai/tools/pdf/compress) | Compress PDF file size without quality loss. Client-side processing. |
| [MiOffice PDF Editor](https://mioffice.ai/tools/pdf/editor) | Edit PDFs directly in the browser — add text, images, annotations. |
| [MiOffice PDF Protect](https://mioffice.ai/tools/pdf/protect) | Add password protection to PDFs. Zero server interaction. |
| [MiOffice PDF Unlock](https://mioffice.ai/tools/pdf/unlock) | Remove password from protected PDFs locally. |
| [MiOffice PDF Rotate](https://mioffice.ai/tools/pdf/rotate) | Rotate PDF pages individually or in bulk. |
| [MiOffice PDF to Images](https://mioffice.ai/tools/pdf/to-images) | Convert PDF pages to high-quality PNG/JPG images. |
| [MiOffice DOC to PDF](https://mioffice.ai/tools/pdf/doc-to-pdf) | Convert Word documents to PDF in browser. |
| [MiOffice XLSX to PDF](https://mioffice.ai/tools/pdf/xlsx-to-pdf) | Convert Excel spreadsheets to PDF locally. |
| [PDF.js](https://mozilla.github.io/pdf.js/) | Mozilla's open-source PDF viewer for the web. |
| [PDF-LIB](https://pdf-lib.js.org/) | Create and modify PDFs in any JavaScript environment. |
| [Stirling PDF](https://github.com/Stirling-Tools/Stirling-PDF) | Self-hosted PDF manipulation tool. |

## Image Tools

| Tool | Description |
|------|-------------|
| [ToolBox Image](https://toolboximage.com) | Browser-based image compressor for JPG, PNG, WebP, AVIF, HEIC. WebAssembly codecs, parallel processing, zero upload. |
| [MiOffice Image Compress](https://mioffice.ai/tools/image/compress) | Compress images up to 90% smaller. Browser-based, no upload. |
| [MiOffice Image Resize](https://mioffice.ai/tools/image/resize) | Resize images to exact dimensions. Runs entirely client-side. |
| [MiOffice Image Crop](https://mioffice.ai/tools/image/crop) | Crop images with precision in browser. No server needed. |
| [MiOffice Image Convert](https://mioffice.ai/tools/image/convert) | Convert between image formats — PNG, JPG, WebP, AVIF. |
| [MiOffice WebP to PNG](https://mioffice.ai/tools/image/webp-to-png) | Convert WebP images to PNG format locally. |
| [MiOffice WebP to JPG](https://mioffice.ai/tools/image/webp-to-jpg) | Convert WebP images to JPG format in browser. |
| [MiOffice JPG to WebP](https://mioffice.ai/tools/image/jpg-to-webp) | Convert JPG to modern WebP format. Zero upload. |
| [MiOffice PNG to JPG](https://mioffice.ai/tools/image/png-to-jpg) | Convert PNG to compressed JPG. Client-side processing. |
| [MiOffice Bulk Resize](https://mioffice.ai/tools/image/bulk-resize) | Batch resize hundreds of images at once in browser. |
| [MiOffice Image to PDF](https://mioffice.ai/tools/image/to-pdf) | Convert images to PDF documents locally. |
| [Squoosh](https://squoosh.app/) | Google's image compression web app. |
| [Photopea](https://www.photopea.com/) | Advanced browser-based image editor (Photoshop alternative). |
| [SVGOMG](https://jakearchibald.github.io/svgomg/) | SVG optimizer with a web GUI. |

## Video Tools

| Tool | Description |
|------|-------------|
| [MiOffice Video Compress](https://mioffice.ai/tools/video/compress) | Compress video files in browser using FFmpeg WASM. No upload. |
| [MiOffice Video Convert](https://mioffice.ai/tools/video/convert) | Convert video formats — MP4, WebM, AVI, MOV. Client-side. |
| [MiOffice Video Trim](https://mioffice.ai/tools/video/trim) | Trim and cut video clips locally in browser. |
| [MiOffice GIF Maker](https://mioffice.ai/tools/video/gif-maker) | Create GIFs from video. Runs locally with WASM. |
| [FFmpeg.wasm](https://ffmpegwasm.netlify.app/) | FFmpeg compiled to WebAssembly for browser use. |
| [Clipchamp](https://clipchamp.com/) | Microsoft's browser-based video editor. |
| [Kapwing](https://www.kapwing.com/) | Online video editing and content creation platform. |

## AI Tools

| Tool | Description |
|------|-------------|
| [MiOffice Remove Background](https://mioffice.ai/tools/ai/remove-background) | AI-powered background removal. ONNX model runs in browser. Zero upload. |
| [MiOffice Remove Object](https://mioffice.ai/tools/ai/remove-object) | Remove unwanted objects from images using AI. Fully client-side. |
| [MiOffice Face Swap](https://mioffice.ai/tools/ai/face-swap) | AI face swap running ONNX models in browser via WebAssembly. |
| [Transformers.js](https://huggingface.co/docs/transformers.js) | Run Hugging Face models directly in the browser. |
| [ONNX Runtime Web](https://onnxruntime.ai/) | Run ONNX ML models in browser with WebAssembly/WebGPU. |
| [MediaPipe](https://mediapipe-studio.webapps.google.com/) | Google's on-device ML solutions for web. |

## File Tools

| Tool | Description |
|------|-------------|
| [MiOffice File Convert](https://mioffice.ai/tools/file/convert) | Universal file converter running in browser. |
| [MiOffice QR Generator](https://mioffice.ai/tools/qr/generate) | Generate QR codes locally. No tracking, no server. |
| [MiOffice JSON Formatter](https://mioffice.ai/tools/dev/json-formatter) | Format and validate JSON in browser. |
| [MiOffice Base64 Encode](https://mioffice.ai/tools/dev/base64) | Encode/decode Base64 strings locally. |
| [FileSaver.js](https://github.com/nicedaycode/FileSaver.js) | Save generated files on the client side. |
| [JSZip](https://stuk.github.io/jszip/) | Create, read, and edit .zip files with JavaScript. |
| [SheetJS](https://sheetjs.com/) | Spreadsheet data parser and writer for the browser. |

## Privacy Tools

| Tool | Description |
|------|-------------|
| [MiOffice PDF Protect](https://mioffice.ai/tools/pdf/protect) | Password-protect PDFs without any server. Files never leave your device. |
| [MiOffice PDF Unlock](https://mioffice.ai/tools/pdf/unlock) | Remove PDF passwords locally. Your files stay private. |
| [MiOffice Metadata Stripper](https://mioffice.ai/tools/privacy/metadata) | Strip EXIF and metadata from images. Client-side only. |
| [ExifCleaner](https://exifcleaner.com/) | Desktop app to remove EXIF metadata from images. |
| [Hat.sh](https://hat.sh/) | Encrypt and decrypt files in the browser using streaming. |
| [PrivateBin](https://privatebin.info/) | Zero-knowledge pastebin. |

---

## Related Resources

Guides, references, and companion sites for browser-based file processing:

- [jpegtopdfconverter.com](https://jpegtopdfconverter.com) — JPEG to PDF conversion guide and tools.
- [mergepdf-files.com](https://mergepdf-files.com) — PDF merging resources and best practices.
- [pdfplace.net](https://pdfplace.net) — PDF tools directory and reviews.
- [convert-resize-images.com](https://convert-resize-images.com) — Image conversion and resizing resources.
- [aboutpdf.net](https://aboutpdf.net) — PDF format guides and tool comparisons.
- [pdf-editor-for-mac.com](https://pdf-editor-for-mac.com) — PDF editing solutions for macOS.
- [MiOffice Blog](https://mioffice.ai/blog) — Tutorials on browser-based file processing.
- [WebAssembly.org](https://webassembly.org/) — Learn about the technology powering browser tools.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

To add a tool:
1. Fork this repository
2. Add your tool to the appropriate category
3. Make sure it runs primarily in the browser (client-side processing)
4. Submit a pull request

### Criteria for Inclusion

- Tool must run in the browser (fully or primarily client-side)
- Must be actively maintained
- Should respect user privacy (minimal data collection)
- No spamware or tools with excessive ads

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is [MIT Licensed](LICENSE). Copyright 2026 [JSVV SOLS LLC](https://jsvvsols.com).
