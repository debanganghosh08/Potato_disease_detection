# 🥔 Potato Disease Detection | Full-Stack AI Web App
![image](https://github.com/user-attachments/assets/0ec4dfba-3635-4535-9431-c901c1b0b254)
# 💻 Tech Stack:
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
---

## 🌟 Project Overview

**Potato Disease Detection** is an AI-powered web application that predicts the health status of a potato plant based on an uploaded image.  
It can detect:

- 🥔 **Early Blight**
- 🥔 **Late Blight**
- 🥔 **Healthy**

The frontend is built with **React.js**, while the backend is a **Flask API** deployed on **Google Cloud Functions**, using a **TensorFlow** deep learning model trained for potato disease classification.

---

## ✨ Live Demo

🔗 [Visit the Live App](https://potato-disease-detection-mu.vercel.app/)

---

## 🏧 Features

- Upload an image of a potato leaf.
- AI model predicts the disease class.
- Displays prediction result with **confidence percentage** (upto **99.99%** accuracy formatting).
- Fully responsive modern UI.
- Cloud-based API hosted on Google Cloud.
- CORS enabled for seamless communication.
- Deployment-ready production build.

---

## 📦 Tech Stack

| Frontend | Backend | AI/ML | Deployment |
|:--------:|:-------:|:-----:|:----------:|
| React.js | Flask (Python) | TensorFlow (CNN model) | Vercel (Frontend) |
| Axios | Google Cloud Functions | Numpy, PIL | GCP Cloud Functions (Backend) |
| FormData API | Storage Bucket (GCP) | | |

---

## 📂 Project Structure

```bash
Potato_disease_detection/
🔻— frontend/          # React app (User Interface)
🔻— backend/           # Google Cloud Function code (Flask)
🔻— README.md
🔻— .gitignore
```

---

## 🚀 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/debanganghosh08/Potato_disease_detection.git
cd Potato_disease_detection
```

---

### 2. Backend Setup (Google Cloud Function)

**a. Install required Python libraries**

```bash
pip install -r backend/requirements.txt
```

**b. Code Explanation**

- Downloads the trained `potatoes.h5` model from Google Cloud Storage.
- Loads model into memory.
- Accepts file uploads (image).
- Predicts the class and returns result as JSON.

**c. Deploy the Flask backend on GCP**  
(You already did this — great!)

**Important:** Make sure CORS headers are handled correctly (already implemented).

---

### 3. Frontend Setup (React)

**a. Navigate to frontend**

```bash
cd frontend
```

**b. Install Node.js packages**

```bash
npm install
```

**c. Create `.env` file**

Inside the `/frontend` folder:

```
REACT_APP_API_URL=https://your-cloud-function-url
```

Replace `your-cloud-function-url` with your deployed GCP URL.

**d. Start Development Server**

```bash
npm start
```

Visit [http://localhost:3000](http://localhost:3000) to view it locally.

---

### 4. Build & Deploy (Production)

**a. Build the frontend**

```bash
npm run build
```

**b. Deploy using Vercel**

- Connect GitHub repo to [Vercel](https://vercel.com/).
- Set environment variables (REACT_APP_API_URL).
- Deploy!

---

## 📚 Future Improvements

- Add more potato disease categories.
- Improve model accuracy with larger dataset.
- Drag & Drop Image Upload.
- Progress loader animation.
- Notification alerts (success/error).

---

## 🧽 Acknowledgements

- [TensorFlow](https://www.tensorflow.org/)
- [Google Cloud Platform](https://cloud.google.com/)
- [Vercel Hosting](https://vercel.com/)
- [React.js](https://reactjs.org/)

---

## 📬 Contact

- **Developer**: [Debangan Ghosh](https://github.com/debanganghosh08)
- **Email**: primusvlog@gmail.com
- **LinkedIn**: [Connect Here!😃](https://www.linkedin.com/in/debangan-ghosh/)

---

🌟 If you like this project, feel free to star it on GitHub!

---

