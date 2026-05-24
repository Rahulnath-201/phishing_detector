# Phishing Email Detection Model

## Overview

Phishing Email Detection Model is a machine learning project developed using Python and Scikit-learn. The model analyzes email text and detects whether an email is phishing or legitimate.

The project uses Natural Language Processing (NLP) techniques and machine learning algorithms to classify emails based on keywords, URLs, and textual content.

---

## Features

- Email text analysis
- URL detection
- Keyword extraction
- Machine learning classification
- Accuracy score display
- Confusion matrix visualization
- Phishing vs Safe prediction

---

## Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Machine Learning Concepts

- Text Vectorization (TF-IDF)
- Logistic Regression
- Train-Test Split
- Confusion Matrix
- Accuracy Evaluation

---

## Project Structure

```text
phishing-email-detection/
│
├── phishing_detector.py
├── emails.csv
├── README.md
 
```

---

## Dataset Format

```csv
text,label
"Congratulations! Click here to claim reward","phishing"
"Meeting scheduled tomorrow at 10 AM","safe"
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/your-username/phishing-email-detection.git
```

### Open Folder

```bash
cd phishing-email-detection
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Project

```bash
python phishing_detector.py
```

---

## Example Output

```text
Model Accuracy: 96.5%

Classification Result:
Email is classified as: Phishing
```

---

## Future Improvements

- Deep learning integration
- Real-time email scanning
- GUI using Tkinter
- Web application using Flask
- URL reputation checking
- Email attachment scanning

---

## Learning Outcomes

This project helps in learning:
- Machine Learning basics
- Natural Language Processing
- Email security concepts
- Classification algorithms
- Cybersecurity fundamentals

---

## Author

Rahulnath A

---

## License

This project is developed for educational and internship purposes.
