# PredictiveHR

## 🎯 Overview

PredictiveHR is an intelligent HR Churn Prediction System that helps organizations predict whether an employee is likely to resign or stay in the company. The system uses machine learning algorithms to analyze various employee metrics and provide actionable insights for HR teams.

## 🔗 Repository

[https://github.com/NavvAbhishek/PredictiveHR.git](https://github.com/NavvAbhishek/PredictiveHR.git)

## ✨ Features

- **Employee Churn Prediction**: Predict resignation probability using machine learning
- **Comprehensive Analytics**: Analyze multiple employee factors including:
  - Job Role
  - Distance from Home (km)
  - Remote Work Status
  - Number of Promotions
  - Monthly Income ($)
  - And other relevant metrics
- **Interactive Dashboard**: Modern React-based frontend with responsive design
- **RESTful API**: Fast and scalable FastAPI backend
- **Data Persistence**: PostgreSQL database for secure data storage
- **Machine Learning Integration**: Logistic Regression model for accurate predictions

## 🛠️ Tech Stack

### Frontend
- **React.js** - Modern JavaScript framework
- **Tailwind CSS** - Utility-first CSS framework
- **Vite** - Fast build tool and development server

### Backend
- **FastAPI** - Modern, fast Python web framework
- **Python** - Core programming language
- **Uvicorn** - ASGI server for production

### Database
- **PostgreSQL** - Advanced open-source relational database

### Machine Learning
- **Scikit-learn** - Machine learning library
- **Logistic Regression** - Prediction algorithm
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing

## 🚀 Quick Start

### Prerequisites

- Node.js (v16 or higher)
- Python (v3.8 or higher)
- PostgreSQL (v12 or higher)
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/NavvAbhishek/PredictiveHR.git
   cd PredictiveHR
   ```

2. **Set up the database**
   - Create a PostgreSQL database
   - Note down your database credentials

3. **Configure environment variables**
   Create a `.env` file in the backend folder root directory:
   ```env
   DB_USER=your_database_user
   DB_PASSWORD=your_database_password
   DB_HOST=localhost
   DB_PORT=5432
   DB_NAME=your_database_name
   SECRET_KEY=your_secret_key_here
   ```

### Frontend Setup

1. **Navigate to frontend directory**
   ```bash
   cd frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

The frontend will be available at `http://localhost:5173`

### Backend Setup

1. **Navigate to backend directory**
   ```bash
   cd backend
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Start the backend server**
   ```bash
   uvicorn app.main:app --reload
   ```

The API will be available at `http://localhost:8000`

## 📊 Model Training

The system uses a Logistic Regression model trained on employee data to predict churn probability. The model considers various factors such as:

- Age
- Company Size
- Remote Work
- Monthly Income ($)
- Distance from Home (km)

## 🔧 Usage

1. **Data Input**: Upload employee data or input individual employee metrics
2. **Prediction**: Get churn probability scores for employees
3. **Analytics**: View detailed insights and trends
4. **Export**: Download reports and predictions for further analysis

## 📁 Project Structure

```
PredictiveHR/
├── frontend/                 # React.js frontend
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
├── backend/                  # FastAPI backend
│   ├── app/
│   │   ├── main.py
│   │   ├── models/
│   │   ├── routers/
│   │   └── ...
│   ├── requirements.txt
│   └── ...
├── ml_models/                   # ML models and training scripts
├── data/                     # Sample data and datasets
├── .env.example             # Environment variables template
└── README.md
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- **NavvAbhishek** - *Initial work* - [GitHub Profile](https://github.com/NavvAbhishek)

## 🆘 Support

If you encounter any issues or have questions, please:

1. Check the [Issues](https://github.com/NavvAbhishek/PredictiveHR/issues) page
2. Create a new issue if your problem isn't already listed
3. Provide detailed information about the problem and your environment

## 🔮 Future Enhancements

- [ ] Advanced ML models (Random Forest, XGBoost)
- [ ] Real-time predictions
- [ ] Email notifications for high-risk employees
- [ ] Advanced data visualization
- [ ] Mobile application
- [ ] Integration with popular HR systems

---

**Happy Predicting! 🎯**
