# PDF Extractor

A modern, lightweight, and powerful browser extension to extract and export document previews from **Google Drive** and **direct PDF URLs across the web** into various formats including PDF, images (PNG, JPG, WebP, AVIF, JPEG), or compressed ZIP files.

<div align="center">
  <img src="https://github.com/hamzabellouch/pdf-extractor/blob/main/PDF%20Extractor.jpeg" width="800"/>
</div>

Compatible with all major browsers: **Chrome, Brave, Edge, Opera (Chromium-based)** and **Mozilla Firefox**.



### <a name="Features"></a> ⭐ Features

- **Dual Mode Support:** 
  - **Google Drive Previews:** Extract protected or view-only document previews directly from Google Drive.
  - **Direct PDF URLs:** Extract, convert, or slice pages from any direct PDF file across the web (e.g. `static.googleusercontent.com`, online PDFs, and embedded documents).
- **Multi-Format Support:** Export document previews as **PDF**, **PNG**, **JPG**, **WebP**, **JPEG**, **AVIF**, or **ZIP**.
- **Page Range Settings:** Select specific pages to extract (e.g., start page to end page).
- **Custom Filenames:** Easily customize the name of the exported files.
- **Scroll Speed Control:** Customize the automatic scroll speed for capturing Google Drive preview documents.
- **Theme Adaptation:** Automatically matches your system/browser theme (Dark Mode & Light Mode).
- **Clean UI:** Premium, modern, and user-friendly interface.



### <a name="RepositoryStructure"></a> 📁 Repository Structure

```text

├── chromium/          # Extension build directory for Chrome, Brave, Edge, etc.
│   ├── assets/        # Content scripts, PDF.js assets, popup styles, and popup scripts
│   ├── manifest.json  # Chromium Manifest V3 configuration
│   └── index.html     # Popup entry point
│
├── firefox/           # Extension build directory for Mozilla Firefox
│   ├── assets/        # Content scripts, PDF.js assets, popup styles, and popup scripts
│   ├── manifest.json  # Firefox Manifest V3 configuration (with Gecko ID)
│   └── index.html     # Popup entry point
│
└── .gitignore         # Prevents tracking of OS metadata, IDE configurations, etc.

```



### <a name="InstallationUsage"></a> ⚙️ Installation & Usage

### <a name="ForChromiumBasedBrowsers"></a> 🌐 For Chromium-Based Browsers (Chrome, Brave, Edge, Opera)

1. Open your Chromium-based browser and navigate to:
   - **Google Chrome / Brave / Opera:** `chrome://extensions/`
   - **Microsoft Edge:** `edge://extensions/`

2. Enable **Developer mode**.

3. Click **Load unpacked**.

4. Select the following directory:

```text
chromium/
├── assets/
├── manifest.json
└── index.html
```

5. The extension will be installed and is now ready to use.

### <a name="ForMozillaFirefox"></a> 🦊 For Mozilla Firefox

1. Open **Mozilla Firefox** and navigate to `about:debugging#/runtime/this-firefox`.
2. Click **Load Temporary Add-on...**.
3. Select the following file:

```text
firefox/
└── manifest.json
```

4. The extension is now loaded as a temporary add-on.



### <a name="Privacy & Safety"></a> 🛡️ Privacy & Safety

- **Local Processing:** All conversions, page rendering, and extractions are performed locally in your browser. No data is sent to external servers or databases.
- **Safe & Efficient:** Uses high-performance local Web Workers for client-side PDF rasterization and vector manipulation.



> [!WARNING]
> There is always a possibility of error, so we assume no responsibility for any inaccuracies.


### <a name="Copyright©2026"></a> Copyright © 2026

Thank you for engaging with us. For inquiries or collaboration, please contact:  
hamzabellouchcontact@gmail.com

Stay connected and follow us on:  
[WhatsApp](https://whatsapp.com/channel/0029Vb7MArw0LKZMpjjqOk2P) | [Facebook](https://facebook.com/hamzabellouch1) | [Instagram](https://instagram.com/hamzabellouch0) | [Twitter](https://twitter.com/hamzabellouch0) | [Telegram](https://t.me/hammzabellouch) | [LinkedIn](https://www.linkedin.com/in/hamzabellouch)
