# 🎭 Facial Expression Recognition Web App

A real-time facial expression recognition system using **Python (Flask)**, **FER**, and a modern **HTML/CSS/JavaScript** frontend. This app detects human emotions (e.g., happy, sad, angry) directly from the user's webcam and displays the result live in the browser.

## 🚀 Features

- 🎥 Real-time webcam-based emotion detection
- 🧠 AI-powered facial expression recognition using the `FER` deep learning model
- 📦 REST API built with Flask and OpenCV
- 💻 Clean, responsive frontend interface
- 🌐 Fully deployable on **Vercel**

## 📸 How It Works

1. The browser accesses the user's webcam via JavaScript.
2. A frame is captured every few seconds and sent to the Flask API.
3. The backend decodes the image and runs emotion detection using `FER`.
4. The dominant emotion and confidence score are returned and displayed live.

## 🧰 Tech Stack

| Frontend        | Backend        | AI/ML Model     | Deployment |
|----------------|----------------|-----------------|------------|
| HTML, CSS, JS   | Flask (Python) | FER, MTCNN, OpenCV | Vercel     |

## 📂 Project Structure

```

expression-webapp/
├── api/                # Flask backend
│   └── index.py
├── public/             # Frontend files
│   ├── index.html
│   ├── styles.css
│   └── script.js
├── requirements.txt    # Python dependencies
├── vercel.json         # Vercel deployment config
└── README.md

````
## ⚙️ Installation (For Local Testing)

### 1. Clone the Repo

```bash
git clone https://github.com/yourusername/expression-webapp.git
cd expression-webapp
````

### 2. Set Up a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run Flask API

```bash
cd api
flask run
```

### 5. Open `public/index.html` in a browser

## 🌍 Deployment on Vercel

1. Push the project to a GitHub repository.
2. Go to [https://vercel.com/import](https://vercel.com/import).
3. Import your GitHub repo and deploy.
4. Done! Your app is now live.

> Make sure to include `vercel.json` and `requirements.txt` in the root directory.

## 🧠 Model Information

* Uses `FER` (Facial Expression Recognition) library
* Supports common emotions: **angry, disgust, fear, happy, sad, surprise, neutral**
* Built-in support for MTCNN face detection for high accuracy

## 📄 License

This project is for personal or educational use. No license attached.

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

## 👤 Author

* **Sohan** – [@Afmtechz](https://github.com/Afmtechz) [@sohan__9705](https://instagram.com/sohan__9705)
