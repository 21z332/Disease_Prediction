# Elite-Coders
Inaccurate diagnosis and treatment decisions.For this develop clinical decision support systems that leverage artificial intelligence and machine learning algorithms to assist healthcare professionals in making accurate and evidence-based diagnoses and treatment recommendations.

**Medical Diagnosis Web Application**
**Overview**
This web application serves as a medical diagnosis tool that predicts potential diseases based on symptoms provided by users. It also includes a feature to analyze X-ray images for pneumonia detection. The application utilizes machine learning models trained on medical datasets to provide accurate predictions.

**Features**
Symptom-based Diagnosis:
Users can input symptoms, and the application predicts potential diseases using machine learning algorithms.
The application evaluates multiple models, including Decision Trees, Random Forests, Naive Bayes, and K Nearest Neighbors, to provide the most accurate diagnosis.
Additionally, the application recommends treatments based on the predicted disease.

X-ray Image Analysis:
Users can upload X-ray images for analysis to detect pneumonia.
The application employs a Convolutional Neural Network (CNN) model trained on X-ray images to classify them as either showing signs of pneumonia or being normal.

**Installation**
Download Model Files:
Download the pre-trained model files for symptom prediction and X-ray analysis.
Place the model files in the appropriate directories (models/).

Run Application:
python app.py or flask run

Access Application:
Open a web browser and go to http://localhost:5000 to access the application.

**Usage**
Symptom-based Diagnosis:
Enter symptoms on the homepage and submit the form to receive a predicted disease and recommended treatment.
X-ray Image Analysis:
Navigate to the X-ray analysis page.
Upload an X-ray image using the provided form.
Submit the form to receive the classification result (normal or pneumonia).

**Technologies Used**
Python: Backend development and machine learning model training.
Flask: Web framework for building the application.
PyTorch: Deep learning library used for image analysis.
scikit-learn: Library for machine learning algorithms and data preprocessing.
PIL (Python Imaging Library): Used for image processing.

**Dataset for Xray based Pneumonia Detection:**
https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

**Demo video:**
https://youtu.be/vNJNF8XUDj0?si=AxKmMc6McfBdm1H_


**Contributors:**
Akshayaa M , Dhanya S, Prathibha G , Sreenithi R


