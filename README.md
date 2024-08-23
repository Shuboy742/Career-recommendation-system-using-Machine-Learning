# Career Recommendation for Future Skills

This project was developed as part of the Smart India Hackathon 2022. It is a web-based application that provides career recommendations for future skills using machine learning algorithms. The application is designed to help users make informed decisions about their careers based on various factors such as location, education, and personal interests.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Here is a view of the actual website](#Here-is-a-view-of-the-actual-website)

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

## Here is a view of the actual website

1)Home Page

![2023-07-25 (1)](https://github.com/user-attachments/assets/53991646-e92f-4cde-ac07-0676ef14ac15)


![2023-07-25 (2)](https://github.com/user-attachments/assets/a1d17539-960c-4976-b082-5f37464d69d3)



<br>2)Career Form

![2023-07-25 (3)](https://github.com/user-attachments/assets/b2d1ac05-f718-4adc-a3f7-b723591b20dd)


![2024-08-23 (11)](https://github.com/user-attachments/assets/882d4e54-2da7-4d95-9078-233756952cf0)


![2024-08-23 (12)](https://github.com/user-attachments/assets/5b03c0e0-c57a-4aba-974b-f39e69443483)



<br>3)Job Recommendation

![2024-08-23 (13)](https://github.com/user-attachments/assets/b2189ffc-9eb2-43ba-8ad9-705012c97cee)


![2024-08-23 (14)](https://github.com/user-attachments/assets/b4ece6ab-9844-4215-8987-6284c06b44dc)



<br>4)Course Recommendation

![2024-08-23 (13)](https://github.com/user-attachments/assets/521c5e35-a05f-4308-a481-543f156ae453)


![2024-08-23 (15)](https://github.com/user-attachments/assets/07dc997c-5ec0-4a65-98ec-b268fabbe59d)



<br>5)Chatbot Interaction

![2024-08-23 (17)](https://github.com/user-attachments/assets/e04d48eb-f9c4-4531-84e9-939a7a4f5e07)



<br>6)Contact Us Page

![2024-08-23 (18)](https://github.com/user-attachments/assets/edcc3c66-a8e3-4829-909f-138fa68b430b)

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
