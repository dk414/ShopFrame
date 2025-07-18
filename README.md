# WindowShop_AI

# 🛍️ WindowShop.ai

**An AI-powered product search engine for video content**  

---

## 🚀 Overview

**WindowShop.ai** bridges the gap between entertainment and e-commerce by allowing users to **shop directly from videos**. Leveraging advanced AI models, it detects and identifies products in video frames and maps them to real-world items, enabling a seamless click-to-buy experience.

---

## 🧠 Key Features

- 🎯 **Object Detection with YOLOv8**  
  Accurately detects products within video frames in real-time.

- 🧩 **Image Similarity Search with CLIP**  
  Matches detected items with product listings using OpenAI's CLIP model for high precision.

- 🖼️ **Rich Product Metadata Integration**  
  Displays product name, link, and image from a pool of **500+ mapped products**.

- 📈 **High Engagement**  
  Achieved an **85%+ click-through rate** during live demo sessions.

- ✅ **Reliable Performance**  
  Boasts a **mean detection accuracy of 92%** on a diverse product dataset.

---

## 🧰 Tech Stack

- **Backend**: Python
- **Deep Learning**: PyTorch
- **Object Detection**: YOLOv8
- **Image Matching**: CLIP (Contrastive Language–Image Pretraining)
- **Image Processing**: PIL (Python Imaging Library)

---

## 📦 How It Works

1. **Extract Frames** from input video.
2. **Detect Products** in each frame using YOLOv8.
3. **Compute Similarity** between detected product regions and a product dataset using CLIP.
4. **Map to Product Listings**, enriching results with metadata and image URLs.
5. **Generate Output** with clickable product links, image previews, and labels.

---

## 📊 Results

| Metric                  | Value         |
|------------------------|---------------|
| Click-Through Rate     | 85%+ (Demo)   |
| Mean Detection Accuracy| 92%           |
| Product Mapping Support| 500+ Products |

---


---


---

## 📌 Future Improvements

- Add voice-based product queries.
- Expand product catalog via web scraping.
- Real-time mobile/web integration.

---

## 📸 Demo Preview

*(Add a few screenshots or a demo GIF here if available)*

---

## 📎 License

MIT License. See the [`LICENSE`](./LICENSE) file for details.
