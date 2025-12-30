# Image-Captioning-VLM

**Vision–Language Model (VLM) for Automatic Image Captioning using BLIP-2**

> Generate rich, human-like textual descriptions from images using a state-of-the-art Vision–Language Model.

---

## 📌 Overview

**Image-Captioning-VLM** is a deep learning–based project that leverages **Salesforce’s BLIP-2 Vision–Language Model** to automatically generate descriptive captions for images.

This project demonstrates how **vision encoders + large language models (LLMs)** can be combined to perform multimodal reasoning — a core concept behind modern AI systems such as GPT-4V, Gemini, and Claude Vision.

---

## ✨ Key Features

* 🔍 **Vision–Language Understanding (VLM)**
* 🧠 Powered by **BLIP-2 (Bootstrapped Language-Image Pretraining)**
* 🖼️ Supports **JPEG, PNG, JPG** image formats
* 📝 Outputs **natural language captions**
* 🚀 Runs efficiently on **Google Colab (T4 GPU recommended)**
* 🔐 Uses **Hugging Face Inference API**
* 📓 Fully implemented in **Jupyter Notebook**
* 🎯 Beginner-friendly, research-ready structure

---

## 🧠 Model Architecture 


![Cool cat](https://github.com/user-attachments/assets/abc7358d-4412-4ff3-a7e8-02a977ed6124)

### Model Used

* **BLIP-2** by Salesforce
  (`Salesforce/blip2-flan-t5-xl` or similar)

BLIP-2 bridges vision and language by:

* Extracting visual features using a frozen vision encoder
* Translating visual embeddings into language-compatible representations
* Generating captions using an LLM without retraining the full model

---

## 📂 Repository Structure

```
Image-Captioning-VLM/
│
├── Image_Captioning.ipynb   # Main implementation notebook
├── README.md                # Project documentation
├── LICENSE                  # MIT License
└── .gitignore               # Ignored files
```

---

## 🛠️ Tech Stack

| Component | Technology                 |
| --------- | -------------------------- |
| Language  | Python                     |
| Framework | PyTorch                    |
| Model     | Salesforce BLIP-2          |
| Platform  | Google Colab               |
| API       | Hugging Face Inference API |
| Notebook  | Jupyter                    |

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/samnaveenkumaroff/Image-Captioning-VLM.git
cd Image-Captioning-VLM
```

---

### 2️⃣ Open in Google Colab (Recommended)

1. Go to **Google Colab**
2. Click **File → Open Notebook**
3. Select **GitHub**
4. Paste this repository URL:

   ```
   https://github.com/samnaveenkumaroff/Image-Captioning-VLM
   ```
5. Open `Image_Captioning.ipynb`

---

### 3️⃣ Enable GPU 

For best performance:

```
Runtime → Change runtime type → Hardware Accelerator → GPU
```

✅ **Recommended GPU**: `T4`

---

## 🔐 Getting a Hugging Face API Token

BLIP-2 requires access via Hugging Face.

### Step-by-Step Guide

1. Visit 👉 [https://huggingface.co](https://huggingface.co)
2. Sign up / Log in
3. Go to **Settings → Access Tokens**
4. Click **New Token**
5. Choose:

   * Name: `Image-Captioning`
   * Role: **Read**
6. Copy the token

---

### 🔑 Add Token in Google Colab

```python
from huggingface_hub import login
login("YOUR_HUGGING_FACE_API_TOKEN")
```

⚠️ **Never commit your token to GitHub**

---

## 🖼️ Supported Image Formats

* `.jpg`
* `.jpeg`
* `.png`

You can upload images directly in Colab or load them via file paths.

---

## 🧪 Example Output

<img width="804" height="806" alt="image" src="https://github.com/user-attachments/assets/ff8e0d10-858e-41e6-b697-cdaab2fd60e1" />


---

## 🎯 Use Cases

* 📸 Automated image annotation
* ♿ Accessibility (screen readers)
* 🧾 Media asset tagging
* 🤖 Multimodal AI research
* 📊 Dataset labeling
* 🛍️ E-commerce product descriptions

---

## 📈 Future Improvements

* 🔄 Batch image captioning
* 🌍 Multilingual captioning
* 🧠 Fine-tuning on custom datasets
* 🎥 Video captioning extension

---

## 📜 License

This project is licensed under the **MIT License**
You are free to use, modify, and distribute with attribution.

---

## 👨‍💻 Author

**Sam Naveenkumar V**

> *AI Research | Vision-Language Models | Generative AI*

Made with ❤️ .

---

## 🌐 Connect With Me

📧 **Email**:
[samnaveenkumaroff@gmail.com](mailto:samnaveenkumaroff@gmail.com)

💼 **LinkedIn**:
[https://www.linkedin.com/in/sam-naveenkumar-v/](https://www.linkedin.com/in/samnaveenkumaroff/)

🐙 **GitHub**:
[https://github.com/samnaveenkumaroff](https://github.com/samnaveenkumaroff)

✍️ **Medium**:
[https://medium.com/@samnaveenkumaroff](https://medium.com/@samnaveenkumaroff)

📸 **Portfolio / Projects**:
[https://github.com/samnaveenkumaroff?tab=repositories](https://github.com/samnaveenkumaroff/)

---

## ⭐ Support

If you found this project helpful:

* ⭐ Star the repository
* 🍴 Fork it
* 🐛 Open issues
* 🤝 Contribute improvements

---

> **“Vision + Language is the foundation of general intelligence.”**

🚀 Happy Coding & Research!
