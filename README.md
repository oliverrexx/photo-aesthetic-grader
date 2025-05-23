# 📷 Photo Aesthetic Grader

A simple, fast tool for automatically scoring the aesthetic quality of images using a machine learning model, with a fully interactive visual explorer powered by [FiftyOne](https://voxel51.com/).

Created by **Oliver Rex and Isabella Crowe** 🎓

---

## ✨ Features

- 📊 Scores images 1–10 using [Aesthetic Predictor v2.5](https://github.com/discus0434/aesthetic-predictor-v2-5)
- 🧠 Based on CLIP + SigLIP for modern generalization
- 🖼️ Built-in [FiftyOne](https://voxel51.com/) integration to visually explore results
- 🧪 Great for testing photo quality, lighting, and filtering high/low-scoring images

---

## 🖥️ Demo

![Preview](preview.png)


> Automatically sorted by aesthetic score. Click, tag, filter, and explore photos visually.

---

## 🚀 Quick Start

[Download Python 3.10.11](https://www.python.org/downloads/release/python-31011/)

**After Installing Python 3.10**
```bash
# 1. Clone the repo
git clone https://github.com/yourusername/photo-aesthetic-grader.git
cd photo-aesthetic-grader

# 2. Create a virtual environment
python -m venv venv
.\venv\Scripts\Activate  # Windows
# or source venv/bin/activate (Mac/Linux)

# 3. Install dependencies
pip install -r requirements.txt

# 4. Install Fiftyone
pip install fiftyone

# 5. Add images to the folder:
#    data/images/

# 6. Run the scorer
python src/run_grader.py
```

