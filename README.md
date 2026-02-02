# Image Converter Pro

A professional, client-side image conversion tool designed for high-performance batch processing. This application operates entirely in the browser, ensuring user privacy and speed by leveraging modern web technologies.

## Features

* **Multi-Format Support**: Supports conversion to WebP, JPEG, and AVIF formats.
* **High Performance**: Utilizes a Worker-based architecture with OffscreenCanvas to perform image processing off the main thread, keeping the interface responsive during heavy tasks.
* **Batch Processing**: Allows users to drag and drop multiple images for simultaneous conversion.
* **Quality Controls**: Adjustable compression quality from 1% to 100%.
* **Automatic Resizing**: Optional maximum width setting to resize images during the conversion process.
* **Optimization Statistics**: Real-time tracking of file size reduction and compression ratios.
* **Flexible Downloads**: Support for individual file downloads or batch downloading multiple processed images as a single ZIP archive.

## Technology Stack

* **HTML5/CSS3**: Modern, responsive user interface.
* **Vanilla JavaScript**: Core application logic without heavy framework dependencies.
* **Web Workers**: Parallel processing for image encoding.
* **OffscreenCanvas**: Hardware-accelerated image manipulation off the main thread.
* **JSZip**: Client-side ZIP generation for batch downloads.

## Usage

1. **Upload**: Drag and drop images (JPG, PNG, GIF, BMP, WEBP) into the designated zone or click to browse files.
2. **Configure**: Select the desired output format, adjust the quality slider, and set an optional maximum width.
3. **Convert**: Click Convert All to start the process. The progress bar at the top indicates completion status.
4. **Download**: Once finished, download individual images or use the Download ZIP button for the entire batch.

## Browser Support

This tool requires a modern browser with support for:

* Web Workers
* OffscreenCanvas
* WebP/AVIF encoding (AVIF support depends on browser implementation)

## License

This project is licensed under the MIT License.

Copyright (c) 2026 mattswymer.
