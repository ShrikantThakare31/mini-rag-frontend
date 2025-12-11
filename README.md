# 🧠 Mini-RAG Frontend

A simple and lightweight frontend interface for interacting with a Retrieval-Augmented Generation (RAG) system.

## 🚀 Features

* 🔍 Search bar for querying documents
* 📝 Renders AI-generated responses
* 📄 Displays retrieved context chunks
* ⚡ Fast and minimal UI (React / Next.js or Vite depending on your setup)
* 🔗 Connects to backend API (`/rag/query` or similar)

## 🛠️ Tech Stack

* **React / Vite** (or Next.js — update as per your project)
* **Axios / Fetch API** for backend calls
* **TailwindCSS** (if used)
* **RAG Backend API** (FastAPI / Flask / Node — mention yours)

## 📁 Project Structure (example)

```
mini-rag-frontend/
│── src/
│   ├── components/
│   ├── pages/ or views/
│   ├── App.jsx
│   └── index.js
│── public/
│── package.json
│── README.md
```

## ▶️ How to Run the Project

```sh
# install dependencies
npm install

# start development server
npm run dev

# build for production
npm run build
```

## 🔌 API Endpoint Example

Update based on your backend:

```js
POST http://localhost:8000/query

{
  "question": "What is RAG?",
  "top_k": 3
}
```

## 🖼️ UI Flow

1. User enters a query
2. Frontend sends request to backend
3. Backend returns:

   * Final answer
   * Retrieved chunks
4. Frontend displays everything neatly

## 📷 Screenshot (optional)

> Add your UI screenshot here.

## 🧩 Future Enhancements

* Chat history
* Better UI styling
* File upload (PDF / text ingestion)
* Document viewer

## 📜 License

MIT License

---



Would you like to generate the full frontend code too?
