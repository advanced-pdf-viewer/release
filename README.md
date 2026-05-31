# PDF Separations Viewer

PDF Separations Viewer is a Windows desktop application for inspecting PDF color separations, previewing composited channels, and exporting separation images or reconstructed PDF pages.

## Overview

This application is designed for print and prepress users who need to:

- inspect CMYK and spot separations in PDF files
- preview the composited appearance of selected channels
- export separation images or reconstructed PDF pages

## How to use

1. Open a PDF file.
2. Select a page to inspect.
3. Choose available separations or spot colors.
4. Preview the composite result in the viewer.
5. Export images or save a new PDF preview as needed.

## Requirements

- Windows 10 or Windows 11
- Ghostscript installed and available on the system PATH
- The app executable and supporting files kept together in the same folder

## Ghostscript

Ghostscript is required to render PDF separations.

1. Download Ghostscript from the official site: https://www.ghostscript.com/releases/
2. Install the Windows version that matches your system.
3. Make sure `gswin64c.exe` or `gswin32c.exe` is available on your PATH.

If the app reports that Ghostscript is missing, install Ghostscript and restart the application.

## Troubleshooting

- If a PDF does not open, verify the file is a valid PDF.
- If separations do not render, confirm Ghostscript is installed correctly.
- If the app cannot locate Ghostscript, check that `gswin64c.exe` or `gswin32c.exe` is on PATH.
- Keep the app files together in one folder to avoid missing resources.
