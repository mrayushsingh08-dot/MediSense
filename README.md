# MediSense – Personalized Medical Recommendation System

**An intelligent healthcare support system that uses Machine Learning to provide personalized medical recommendations based on user-reported symptoms.**

MediSense is a machine learning-based healthcare project designed to help users understand potential health conditions based on their symptoms. The system analyzes symptom inputs and provides relevant predictions along with supporting healthcare information, such as precautions, recommended medicines, diet suggestions, and workout guidance, depending on the implemented features.

The project demonstrates how machine learning can be applied to healthcare information systems to make health-related information more accessible and easier to understand.

> **Disclaimer:** MediSense is an educational project and is not a substitute for professional medical advice, diagnosis, or treatment.

## 🌐 Live Demo

**Live Website:** https://medisenseofficials.vercel.app/

## ✨ Key Features

* **Symptom-Based Prediction:** Predicts potential diseases based on user-selected symptoms.
* **Personalized Recommendations:** Provides relevant healthcare information based on the prediction.
* **Medicine Information:** Displays medicine-related recommendations where supported by the system.
* **Precautions and Guidance:** Presents precautions, diet suggestions, and workout guidance where available.
* **Interactive Web Interface:** Allows users to interact with the system through a user-friendly interface.
* **Machine Learning Integration:** Uses a trained machine learning model to generate predictions.
* **Healthcare Information Access:** Organizes relevant health information in one place.

## 🎯 Project Objectives

* Develop a machine learning-based system for symptom analysis and disease prediction.
* Provide relevant healthcare information through a simple web interface.
* Demonstrate the practical application of machine learning in healthcare.
* Improve the accessibility and presentation of health-related information.

## 🛠️ Technology Stack

| Technology       | Purpose                                 |
| ---------------- | --------------------------------------- |
| Python           | Core programming and backend logic      |
| Flask            | Web application framework               |
| HTML5            | Web page structure                      |
| CSS3             | Styling and responsive design           |
| JavaScript       | Client-side interactivity               |
| Scikit-learn     | Machine learning model development      |
| Pandas           | Dataset processing and manipulation     |
| NumPy            | Numerical operations                    |
| Jupyter Notebook | Data analysis and model experimentation |

## ⚙️ How It Works

1. **Input Symptoms:** The user selects symptoms through the web interface.
2. **Data Processing:** The application converts the selected symptoms into the format expected by the trained model.
3. **Disease Prediction:** The machine learning model predicts a potential disease based on the input features.
4. **Information Retrieval:** The application retrieves relevant healthcare information associated with the prediction.
5. **Display Results:** The prediction and available recommendations are displayed to the user.

## 🔬 Methodology

* **Data Collection:** Use a symptom and disease dataset suitable for the prediction task.
* **Data Preprocessing:** Clean and transform the dataset into a format suitable for model training.
* **Model Training:** Train and evaluate a machine learning classification model.
* **Prediction and Integration:** Integrate the trained model with the Flask application to process user inputs and display results.

## 📁 Project Structure

```text
MediSense/
├── datasets/
│   ├── description.csv
│   ├── diets.csv
│   ├── medications.csv
│   ├── precautions_df.csv
│   ├── symptoms_df.csv
│   ├── workout_df.csv
│   └── Training.csv
├── models/
│   └── svc.pkl
├── static/
│   ├── css/
│   ├── js/
│   └── images/
├── templates/
│   ├── index.html
│   ├── about.html
│   ├── contact.html
│   ├── docmeet.html
│   ├── blog.html
│   ├── navbar.html
│   └── footer.html
├── main.py
├── app.py
├── requirements.txt
├── .gitignore
├── README.md
├── Medicine Recommendation System.ipynb
└── svc.pkl
```

*Note: The structure above represents the main project files. Some folders and filenames may vary as the project evolves.*

## 🚀 Getting Started

### Prerequisites

* Python 3.11
* pip package manager
* Git

### 1. Clone the Repository

```bash
git clone https://github.com/mrayushsingh08-dot/MediSense.git
cd MediSense
```

### 2. Create a Virtual Environment

**Windows:**

```powershell
python -m venv .venv
.venv\Scripts\activate
```

**Linux / macOS:**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install Dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Run the Application

```bash
python main.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000/
```

Ensure that the required dataset and trained model files are available at the locations expected by the application.

## 📊 Expected Outcome

MediSense demonstrates a web-based machine learning workflow in which user-provided symptoms are processed to generate disease predictions and display relevant healthcare information. It combines data processing, model inference, and web development in a single application.

## 🔮 Future Enhancements

* Improve prediction performance through additional data validation and model evaluation.
* Add user accounts and secure health-history management.
* Integrate verified healthcare information from reliable medical sources.
* Improve mobile responsiveness and accessibility.
* Add multilingual support for a wider range of users.
* Explore integration with healthcare professionals for appropriate clinical review.

## 🔐 Privacy and Security

* Avoid submitting personally identifiable or sensitive medical information to an unverified deployment.
* Keep credentials and secret keys out of source control.
* Validate user inputs and handle application errors safely.
* Use appropriate access controls if personal health data is introduced.

## ⚠️ Medical Disclaimer

MediSense is intended for educational and informational purposes only. Its predictions and recommendations may be inaccurate or incomplete and must not be used as the basis for self-diagnosis, medication selection, or treatment decisions. Consult a qualified healthcare professional for medical concerns.

## 👨‍💻 Author

**Ayush Singh**
Computer Science and Engineering Student

* **GitHub:** [mrayushsingh08-dot](https://github.com/mrayushsingh08-dot)
* **Live Project:** [MediSense](https://medisenseofficials.vercel.app/)

---

⭐ If you find this project interesting, consider giving the repository a star.

**Built as a Machine Learning and Web Development project focused on healthcare information and personalized recommendations.**

