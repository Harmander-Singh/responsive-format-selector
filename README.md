# 🖼️ Responsive File Format Converter (Client-Side)

A fully responsive, client-side file converter UI built with HTML, CSS, and JavaScript. Users can upload image files and convert them to JPG, PNG, WebP, or AVIF formats - directly in the browser using the Canvas API.

---

## ✨ What's Working

### 🖼️ Real Image Conversion
- ✅ **Canvas-based conversion** using the HTML5 Canvas API
- ✅ **Supports JPG, PNG, WebP, and AVIF** (with WebP fallback for unsupported formats)
- ✅ **Preserves image quality** during conversion
- ✅ **Handles various image inputs** including PNG, JPG, etc.

### 📥 Automatic Downloads
- ✅ **Each converted file downloads automatically**
- ✅ **Original filenames preserved**, only the extension changes
- ✅ **Cross-browser compatible downloads** using Blob + Object URLs
- ✅ **Displays total size of converted files**

### ⚡ Enhanced User Experience
- ✅ **Real-time conversion status** ("Converted" / "Failed")
- ✅ **Visual file list feedback with file size and name**
- ✅ **Error handling** for failed conversions
- ✅ **Progress bar** updates during actual conversion

### 🛠️ Technical Details
- ✅ **Memory-efficient** (cleans up object URLs)
- ✅ **Uses Blobs** for safe, browser-native file downloads
- ✅ **MIME type detection** for each target format
- ✅ **Works in all modern browsers** (Chrome, Firefox, Safari, Edge)

---

## 🧪 How It Works

1. **Select Format** → Choose output format (JPG, PNG, WebP, AVIF)
2. **Upload Files** → Drag & drop or select from device
3. **Convert** → Click "Convert Files"
4. **Actual Processing** → Images are converted using Canvas API
5. **Auto Download** → Files are automatically downloaded
6. **Status Updates** → Each file shows real-time status

---

## 📸 Preview

![Preview](https://raw.githubusercontent.com/harmander-singh/responsive-format-selector/main/preview.png)

---

## 🚀 Live Demo

🔗 [https://harmander-singh.github.io/responsive-format-selector/](https://harmander-singh.github.io/responsive-format-selector/)

---

## 📂 File Structure

```text
responsive-format-selector/
├── index.html         # Main UI with all logic and styles
├── preview.png        # Screenshot
├── LICENSE            # MIT License file
└── README.md          # This documentation
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).  
You are free to use, modify, and distribute it for personal or commercial use.

---

## 🙌 Author

Made with 💙 by [@harmander-singh](https://github.com/harmander-singh)  
Contributions, stars, and feedback are welcome!
