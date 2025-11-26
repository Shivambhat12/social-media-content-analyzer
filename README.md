# Social Media Content Analyzer

A professional AI-powered tool that extracts text from PDFs and images, analyzes the content with Gemini AI, and provides smart improvement suggestions to help increase audience reach and clarity.

---

## Features

* **Text extraction from PDFs**
* **OCR-based text extraction from images**
* **AI-powered content analysis using Gemini**
* **Suggestions to improve engagement, clarity, and reach**
* **Clean UI built with React & Tailwind CSS**
* **Secure file uploads using Multer**

---

##  Tech Stack

### **Frontend**

* React.js
* Tailwind CSS

### **Backend**

* Node.js
* Express.js
* Multer (file upload handling)
* Gemini AI API

### **Database**

*  No database required

---

##  Folder Structure

```
/social-media-content-analyzer
│── frontend
│   ├── src
│   ├── public
│── backend
│   ├── routes
│   ├── controllers
│   ├── utils
│── README.md
```

---

##  Installation

Follow these steps to run the project locally.

###  Clone the repository

```
git clone <your-repo-link>
cd social-media-content-analyzer
```

###  Install frontend dependencies

```
cd frontend
npm install
```

###  Install backend dependencies

```
cd ../backend
npm install
```

###  Setup environment variables

Create a `.env` file inside **backend** and add:

```
PORT=5000
GEMINI_API_KEY=xxxxxxxxxxxxxxxxxxxxxxxxxx...
```

---

## Running the Project

### Start Backend

```
cd backend
npm start
```

### Start Frontend

```
cd frontend
npm run dev
```

**Frontend URL:**

```
http://localhost:5173
```

**Backend URL:**

```
http://localhost:5000
```

---

##  How to Use

1. Upload content (PDF or image containing text)
2. Click **Upload** → The system extracts text
3. After text extraction, click **Analyze**
4. Gemini AI processes the text and provides:

   * Content quality insights
   * Improvement suggestions
   * Suggestions for better reach and engagement


