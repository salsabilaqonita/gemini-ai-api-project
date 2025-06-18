# ✨ Gemini Flash API

Created by **Salsabila Qonita Kaltsum**

Welcome to **Gemini Flash API** — a simple and powerful RESTful API built with **Express.js**, integrated with **Google Generative AI (Gemini 1.5 Flash)**. This API enables you to send text prompts, images, or documents and receive intelligent responses powered by Google's Gemini model.

---

## 📦 Features

- `POST /generate-text`  
  Generate text responses based on a custom prompt.

- `POST /generate-from-image`  
  Analyze and interpret uploaded images using multimodal AI.

- `POST /generate-from-document`  
  Extract insights or summaries from uploaded documents (PDF, DOCX, or TXT).

---

## ⚙️ Installation

Follow the steps below to set up the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/gemini-flash-api.git
cd gemini-flash-api
```

### 2. Initialize the Project and Install Dependencies

```bash
npm init -y
npm install express dotenv multer @google/generative-ai
```

### 3. Create a `.env` File

Make a `.env` file in the root directory and add your API credentials:

```env
GEMINI_API_KEY=your_google_generative_ai_api_key
PORT=3000
```

---

## 🚀 Getting Started

To start the server, run:

```bash
node index.js
```

Once the server is running, you can start sending requests to the available endpoints.

---

## 🧠 Built With

- [Express.js](https://expressjs.com/) – Fast and minimalist web framework for Node.js
- [@google/generative-ai](https://www.npmjs.com/package/@google/generative-ai) – SDK to access Gemini 1.5 Flash
- [Multer](https://www.npmjs.com/package/multer) – Middleware for handling file uploads
- [Dotenv](https://www.npmjs.com/package/dotenv) – Loads environment variables from `.env` file

---

## 🤝 Contributing

Pull requests are welcome! If you’d like to improve this API or add more features, feel free to fork the repo and submit a PR.

---

## 📬 Contact

For any questions or feedback, feel free to reach out to **Salsabila Qonita Kaltsum** via [LinkedIn](https://www.linkedin.com/in/salsabilaqonitakaltsum/)
