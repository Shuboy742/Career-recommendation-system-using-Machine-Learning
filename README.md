# Career Recommendation for Future Skills

This project was developed as part of the Smart India Hackathon 2022. It is a web-based application that provides career recommendations for future skills using machine learning algorithms. The application is designed to help users make informed decisions about their careers based on various factors such as location, education, and personal interests.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Career Recommendations**: Get personalized career suggestions based on your inputs.
- **Job Suggestions**: Find jobs that match your qualifications and preferences.
- **Course Recommendations**: Discover courses to enhance your skills and improve your career prospects.
- **Chatbot Integration**: Interact with a chatbot to get career advice.
- **Real-Time Data Upload**: Automatically upload data to a backend for analysis.

## Technologies Used

- **Backend**: Flask (Python)
- **Machine Learning**: Joblib for model loading and prediction
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **APIs**: Hugging Face API for chatbot integration
- **Miscellaneous**: Requests library for API calls, Flask-RESTful for API creation

## Project Structure

```plaintext
├── templates
│   ├── index.html
│   ├── speak_to_an_expert.html
│   ├── forms.html
│   ├── forms1.html
│   ├── forms2.html
│   ├── display.html
│   ├── display1.html
│   ├── display2.html
│   ├── login.html
│   ├── signup.html
├── static
│   ├── css
│   ├── js
│   ├── images
├── app.py
├── Model.joblib
├── ModelJob.joblib
├── Modelcourse.joblib
├── fire.py
├── realtime.py
└── README.md

To include the screenshots in your README.md, you can add a section for screenshots and embed the images. Below is the updated README.md:

markdown
Copy code
# Career Recommendation for Future Skills

This project was developed as part of the Smart India Hackathon 2022. It is a web-based application that provides career recommendations for future skills using machine learning algorithms. The application is designed to help users make informed decisions about their careers based on various factors such as location, education, and personal interests.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Career Recommendations**: Get personalized career suggestions based on your inputs.
- **Job Suggestions**: Find jobs that match your qualifications and preferences.
- **Course Recommendations**: Discover courses to enhance your skills and improve your career prospects.
- **Chatbot Integration**: Interact with a chatbot to get career advice.
- **Real-Time Data Upload**: Automatically upload data to a backend for analysis.

## Technologies Used

- **Backend**: Flask (Python)
- **Machine Learning**: Joblib for model loading and prediction
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **APIs**: Hugging Face API for chatbot integration
- **Miscellaneous**: Requests library for API calls, Flask-RESTful for API creation
- **Databse**: MySQL
- **AI Bots**: Generative Adversarial Network (GAN)

## Project Structure

```plaintext
├── templates
│   ├── index.html
│   ├── speak_to_an_expert.html
│   ├── forms.html
│   ├── forms1.html
│   ├── forms2.html
│   ├── display.html
│   ├── display1.html
│   ├── display2.html
│   ├── login.html
│   ├── signup.html
├── static
│   ├── css
│   ├── js
│   ├── images
├── app.py
├── Model.joblib
├── ModelJob.joblib
├── Modelcourse.joblib
├── fire.py
├── realtime.py
└── README.md

#Setup and Installation

1)Clone the repository:
git clone https://github.com/Shuboy742/Career-recommendation-system-using-Machine-Learning.git

2)Navigate to the project directory:
cd Career-recommendation-system-using-Machine-Learning

3)Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

4)Install the required packages:
pip install -r requirements.txt

5)Run the Flask application:
python app.py

#Usage
Home Page: Interact with the main features of the application.
Career Forms: Fill out forms with your details to receive career recommendations.
Job and Course Recommendations: Get suggestions for jobs and courses based on your inputs.
Chatbot: Use the chatbot to get career advice and ask questions.

#Here is a view of the actual website:

1)Home Page

![2023-07-25 (1)](https://github.com/user-attachments/assets/944ecc0e-591c-43c8-9cd8-ec8b1df3033d)

![2023-07-25 (2)](https://github.com/user-attachments/assets/f86a1b8c-e5a3-4b1c-a66d-163baaf7a9cc)


2)Career Form

![2023-07-25 (3)](https://github.com/user-attachments/assets/2b1792af-cc06-4a7e-88c7-058264513491)

![2024-08-23 (11)](https://github.com/user-attachments/assets/4c3277d5-b881-4e16-9faa-aef17b80cfc0)

![2024-08-23 (12)](https://github.com/user-attachments/assets/482fa8b6-591a-484a-bc4f-1b175cff6f8c)


3)Job Recommendation

![2024-08-23 (13)](https://github.com/user-attachments/assets/9b496a33-b560-4abb-bca6-d2412d6366b4)

![2024-08-23 (14)](https://github.com/user-attachments/assets/f1e47c64-6654-421d-8be7-107332548c32)


4)Course Recommendation

![2024-08-23 (13)](https://github.com/user-attachments/assets/fb88dc42-630b-4e37-80da-fba7ab2a82da)

![2024-08-23 (15)](https://github.com/user-attachments/assets/232f35ea-c61d-44c8-bc7f-8da7592f74a1)


5)Chatbot Interaction

![2024-08-23 (17)](https://github.com/user-attachments/assets/f9a3b264-bf03-47a0-9687-3f4a1e752c55)

6)Contact us page

![2024-08-23 (18)](https://github.com/user-attachments/assets/747020e4-5f0b-49b0-9b54-190ae7d77622)





