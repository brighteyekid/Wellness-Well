
---

# **Wellness-Well: AI-Powered Health Prediction Platform**

<div align="center">
  <img src="/public/favicon.ico" alt="Wellness-Well Logo" width="100"/>

  [![GitHub License](https://img.shields.io/github/license/brighteyekid/Wellness-Well)](https://github.com/brighteyekid/Wellness-Well/blob/main/LICENSE)
  [![GitHub Stars](https://img.shields.io/github/stars/brighteyekid/Wellness-Well)](https://github.com/brighteyekid/Wellness-Well/stargazers)
  [![GitHub Issues](https://img.shields.io/github/issues/brighteyekid/Wellness-Well)](https://github.com/brighteyekid/Wellness-Well/issues)
</div>

---

## 🌟 **Overview**

**Wellness-Well** is an AI-driven health prediction platform that offers early detection and risk assessment for multiple medical conditions. It combines modern web technologies and advanced machine learning algorithms to provide users with accurate, actionable health insights.

---

## 🔍 **Key Features**

- **Multi-Disease Prediction**
  - Heart Disease Risk Assessment
  - Diabetes Risk Analysis
  - Parkinson's Disease Detection
  - Cancer Risk Evaluation
- **Interactive Features**
  - AI-Powered Medical Chatbot
  - Real-time Analysis Dashboard
  - User-friendly Interface
  - Secure Data Processing for Privacy Protection

---

## 🛠️ **Technology Stack**

### **Frontend**
- React 18
- TypeScript
- Tailwind CSS
- Framer Motion
- React Router DOM

### **Backend**
- FastAPI
- Python 3.9+
- Scikit-learn
- Joblib for Model Deployment

### **DevOps & Deployment**
- Docker & Docker Compose
- Render Cloud Platform
- GitHub Actions for CI/CD

---

## 🚀 **Quick Start**

### **Prerequisites**
- Node.js 18+
- Python 3.9+
- Docker (Optional for Deployment)

### **Development Setup**

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/brighteyekid/Wellness-Well.git
   cd Wellness-Well
   ```

2. **Frontend Setup**  
   ```bash
   cd frontend
   npm install
   npm start
   ```

3. **Backend Setup**  
   ```bash
   cd backend
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   pip install -r requirements.txt
   uvicorn app:app --reload
   ```

4. **Using Docker** (Optional)  
   ```bash
   docker-compose up
   ```

5. **Environment Variables**  
   Create a `.env` file in the root directory with the following keys:  
   ```env
   REACT_APP_API_URL=http://localhost:8000
   REACT_APP_HUGGING_FACE_API_KEY=your_key_here
   PORT=8000
   HOST=0.0.0.0
   ```

---

## 🌐 **API Endpoints**

- `GET /health` - Health check endpoint
- `POST /predict/{disease_type}` - Disease prediction endpoint
- Full API documentation is available in the [API Docs](backend/docs).

---

## 📁 **Project Structure**

```
Wellness-Well/
├── frontend/      # React TypeScript application
├── backend/       # FastAPI Python backend
├── docker/        # Docker configuration
├── models/        # ML model files
└── docs/          # Documentation
```

---

## 🤝 **Contributing**

We welcome contributions! Follow these steps to contribute:

1. **Fork** the repository.  
2. **Create a feature branch**:  
   ```bash
   git checkout -b feature/YourFeatureName
   ```  
3. **Commit your changes**:  
   ```bash
   git commit -m "Add YourFeatureName"
   ```  
4. **Push the branch**:  
   ```bash
   git push origin feature/YourFeatureName
   ```  
5. **Open a Pull Request**.

---

## 📝 **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙏 **Acknowledgments**

- Special thanks to all contributors.
- ML model training dataset providers.
- The open-source community for inspiration and resources.

---

## 📞 **Contact**

For any queries or support, reach out to us:

- **Email**: cb2117@srmist.edu.in

---

<div align="center">
  Made with ❤️ by the Wellness-Well Team  
  <br />
  ⭐ Star this repository if you find it helpful!
</div>

