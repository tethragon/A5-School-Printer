# 📄 PaperSaver-Edu-PDF

**Optimized A4 to A5 PDF Converter for Teachers**

An open-source, client-side web tool designed to help teachers reduce paper consumption. This tool converts standard A4 Portrait PDF documents into 2-in-1 A4 Landscape formats, perfectly sized to be cut in half and pasted into students' A5-sized notebooks.



---

## ✨ Features

- **Privacy First:** All processing happens locally in your browser. No files are uploaded to any server.
- **Smart Imposition:**
    - **Single Page:** Automatically duplicates the page side-by-side (2-in-1) so you get two copies per A4 sheet.
    - **Even Pages:** Pairs pages normally (1-2, 3-4, etc.).
    - **Odd Pages (>1):** Splits the output into two files:
        - **Part A:** All complete pairs.
        - **Part B:** The last page duplicated side-by-side (to save paper when printing for half the class).
- **A5 Optimized:** Automatically scales and fits content into landscape halves.
- **Cutting Guide:** Adds a dashed vertical line in the middle to guide the paper cutter (guillotine).
- **Automatic Naming:** Files are saved with the suffix `_2in1_landscapew` for easy organization.

---

## 🛠️ How to Use

1. **Open the Tool:** Open `index.html` (or the hosted GitHub Pages link) in any modern browser.
2. **Drag & Drop:** Drag your A4 PDF file into the designated area.
3. **Download:** - If the PDF has an even number of pages, one file will download.
   - If it has an odd number of pages, **two** files will download automatically.
4. **Print & Cut:**
   - Print the files.
   - Use the dashed line to cut the A4 sheets into two A5 flyers.

---

## 💡 Economic Printing Strategy for Schools

This tool follows the **"Teacher's Logic"**:
- **Scenario:** You have a 3-page PDF and 20 students.
- **Normal way:** You would print 20x3 = 60 sheets of A4.
- **PaperSaver way:** - You get **Part A** (Pages 1 & 2). Print 20 copies.
    - You get **Part B** (Page 3 duplicated). Print only **10** copies and cut them in half.
- **Result:** You used **30** sheets instead of 60. **50% Paper Saving!**

---

## 🚀 Technical Stack

- **HTML5 / CSS3** (Modern Dark UI)
- **JavaScript** (ES6+)
- **[pdf-lib](https://pdf-lib.js.org/)** - For high-performance PDF manipulation without a backend.

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

---

*Made with ☕ for teachers who want to save the planet, one photocopy at a time.*
