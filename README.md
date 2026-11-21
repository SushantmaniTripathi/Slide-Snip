

# 🎬 Slide-Snip – YouTube to PDF Slide Extractor

<p align="center">
  <a href="https://github.com/SushantmaniTripathi/Slide-Snip/actions">
    <img src="https://img.shields.io/github/actions/workflow/status/SushantmaniTripathi/Slide-Snip/ci.yml?branch=main" alt="Build Status">
  </a>
  <a href="https://github.com/SushantmaniTripathi/Slide-Snip/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License: MIT">
  </a>
  <a href="https://github.com/SushantmaniTripathi/Slide-Snip/issues">
    <img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg" alt="Contributions Welcome">
  </a>
</p>  

**Slide-Snip** is an AI-powered tool that converts **YouTube lecture videos into concise PDF slides**, automatically detecting **unique/non-redundant frames**. It dramatically reduces manual effort and ensures users get only the most relevant content from lengthy videos.

---

## 📸 Preview

<p align="center">
 <img width="835" height="511" alt="image" src="https://github.com/user-attachments/assets/1de1e0ce-503b-483d-b577-1f60b0cf5e84" />

</p>  

---

## 🚨 Problem

Students and educators often spend hours manually capturing key slides from lecture videos. Duplicate frames and repetitive content slow down the learning process.

---

## 💡 Solution

**Slide-Snip** solves this by:

* Extracting **unique, non-redundant slides** from videos
* Reducing processing time from ~10 minutes to **under 2 minutes**
* Compiling the selected slides into a **ready-to-use PDF**
* Leveraging AI, OCR, and NLP for accurate content extraction

---

## ⚙️ Tech Stack

* **Python** – core scripting and automation
* **OCR & NLP** – extract text and analyze slide content
* **PDFGen** – generate concise PDF slides
* **YouTube API / Video Frame Extraction** – fetch lecture frames efficiently

---

## 🚀 Getting Started

### Prerequisites

* Python 3.x
* pip

### Setup

1. **Clone the repository**

```bash
git clone https://github.com/SushantmaniTripathi/Slide-Snip.git
```

2. **Navigate to the project folder**

```bash
cd Slide-Snip
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Run the extractor**

```bash
python extractor.py --video_url "<YouTube Video URL>" --output "slides.pdf"
```

---

## 🛠 How It Works

1. **Download video frames** from the YouTube link
2. **Detect unique/non-redundant slides**
3. **Extract text** using OCR
4. **Compile results** into a concise PDF

---

## 📡 Roadmap

* [ ] Add multi-language text extraction
* [ ] Improve slide similarity detection using AI embeddings
* [ ] Add a web-based interface for uploading videos
* [ ] Integrate with Google Drive or Dropbox for easy export

---

## 🤝 Contributing

Contributions are welcome! Open issues or submit pull requests to improve functionality.

---

## 📜 License

This project is licensed under the **MIT License** – see [LICENSE](LICENSE) for details.

---

**Contact:** [sushantmanitripathiji@gmail.com](mailto:sushantmanitripathiji@gmail.com)

