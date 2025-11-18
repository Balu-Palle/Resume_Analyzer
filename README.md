<<<<<<< HEAD
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
=======
# Resume Analyzer

## 📋 Requirements

### Backend
- Python 3.8+
- Flask
- PyPDF2
- Google Generative AI SDK
- Flask-CORS
- python-dotenv

### Frontend
- Node.js 16+
- React 18+
- Vite

## 🔧 Installation

### Backend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/sahith-s/resume-analyzer.git
   ```

2. Install backend dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Create a `.env` file in the project root:
   ```
   GEMINI_API_KEY=your_gemini_api_key_here
   ```

   > 📝 Get your API key from [Google AI Studio](https://makersuite.google.com/)

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd resume-analyzer
   ```

2. Install frontend dependencies:
   ```bash
   npm install
   ```

3. Configure the API endpoint:
   - Open `src/config.js` (create if needed)
   - Set the backend URL:
     ```javascript
     export const API_URL = 'http://localhost:5000';
     ```

## 🚀 Running the Application

### Start the Backend Server

```bash
# From the project root (resume-analyzer directory)
python app.py
```

The server will start at http://127.0.0.1:5000

### Start the Frontend Development Server

```bash
# From the frontend directory
npm run dev
```

The React app will be available at http://localhost:5173

## 📚 Project Structure

```
/
├── app.py                  # Flask backend server
├── .env                    # Environment variables (not tracked in git)
├── requirements.txt        # Backend dependencies list
├── resume-analyzer/               # React frontend
│   ├── src/
│   │   ├── components/
│   │   │   ├── Home.jsx    # Landing page component
│   │   │   ├── Upload.jsx  # Resume upload component
│   │   │   └── Analysis.jsx # Results display component
│   │   ├── App.jsx         # Main application component
│   │   └── main.jsx        # Entry point
```

## 🔄 API Endpoints

- `GET /health` - Health check endpoint
- `POST /upload` - Upload and analyze a resume (accepts PDF files)

## 📝 License

[MIT](LICENSE)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
>>>>>>> d65a29d290929c563141cb30bec555630be4ebcf
