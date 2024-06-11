**Potato Disease Classification**

**Overview**
This mobile app, built using React Native, aims to assist farmers in detecting diseases in potatoes, allowing for early intervention and improved crop yields. The app focuses on identifying two major potato diseases:

**1. Early Blight:** Caused by fungi and other similar organisms.

**2. Late Blight:** Caused by the fungal-like oomycete pathogen Phytophthora infestans.

Early detection of these diseases can help farmers maintain healthy crops and increase yield.

**Steps Followed**
**1. Data Collection**
1. Gathered a comprehensive dataset of potato images showing healthy, early blight, and late blight conditions.
2. Utilized various sources including agricultural research databases and farmer-contributed images.

**2. Model Building**
1. Developed a convolutional neural network (CNN) model to classify potato leaf images.
2. rained the model using the collected dataset, ensuring high accuracy in disease detection.

**3. ML Ops**
1. Deployed the trained model using TensorFlow Serving for efficient and scalable model serving.
2. Implemented a backend using FastAPI to handle API requests and integrate with the mobile app.
   
**4. Deployment (GCP)**
1. Deployed the entire application on Google Cloud Platform (GCP) for robust and reliable performance.
2. Leveraged GCP services for hosting the backend and serving the model, ensuring seamless operation.

**Features**
**1. Disease Detection:** Upload an image of a potato leaf to detect early blight or late blight.

**2. User-friendly Interface:** Easy-to-use mobile interface for farmers to quickly analyze their crops.

**3. Real-time Results:** Get instant feedback on the health of your potato crops.

**Technology Stack**
1. Frontend: **React Native**
2. Backend: **FastAPI**
3. Model Serving: **TensorFlow Serving**
4. Cloud Platform: **Google Cloud Platform (GCP)**
