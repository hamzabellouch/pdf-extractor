# PDF Extractor Beta

A modern, lightweight, and powerful browser extension to extract and export document previews from Google Drive into various formats including PDF, images (PNG, JPG, WebP, AVIF), or compressed ZIP files.

<div align="center">
  <img src="https://github.com/hamzabellouch/pdf-extractor/blob/main/PDF%20Extractor.jpeg" width="800"/>
</div>

Compatible with all major browsers: **Chrome, Brave, Edge, Opera (Chromium-based)** and **Mozilla Firefox**.



### <a name="Features"></a> ⭐ Features

- **Multi-Format Support:** Export document previews as **PDF**, **PNG**, **JPG**, **WebP**, **JPEG**, **AVIF**, or **ZIP**.
- **Page Range Settings:** Select specific pages to extract (e.g., start page to end page).
- **Custom Filenames:** Easily customize the name of the exported files.
- **Scroll Speed Control:** Customize the automatic scroll speed for capturing preview documents.
- **Theme Adaptation:** Automatically matches your system/browser theme (Dark Mode & Light Mode).
- **Clean UI:** Premium, modern, and user-friendly interface.



### <a name="RepositoryStructure"></a> 📁 Repository Structure

```text

├── chromium/          # Extension build directory for Chrome, Brave, Edge, etc.
│   ├── assets/        # Content scripts, popup styles, and popup scripts
│   ├── manifest.json  # Chromium Manifest V3 configuration
│   └── index.html     # Popup entry point
│
├── firefox/           # Extension build directory for Mozilla Firefox
│   ├── assets/        # Content scripts, popup styles, and popup scripts
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

- **Local Processing:** All conversions and extractions are performed locally in your browser. No data is sent to external servers or databases.
- **No Permissions Sprawl:** The extension only runs on Google Drive file previews (`https://drive.google.com/file/d/*/view*`, `https://drive.google.com/drive/*`).



> [!WARNING]
> There is always a possibility of error, so we assume no responsibility for any inaccuracies.


### <a name="Copyright©2026"></a> Copyright © 2026

Thank you for engaging with us. For inquiries or collaboration, please contact:  
hamzabellouchcontact@gmail.com

Stay connected and follow us on:  
[Facebook](https://facebook.com/hamzabellouch1) | [Instagram](https://instagram.com/hamzabellouch0) | [Twitter](https://twitter.com/hamzabellouch0) | [Telegram](https://t.me/hammzabellouch) | [LinkedIn](https://www.linkedin.com/in/hamzabellouch)
