# Task: Write a ChatGPT Prompt which takes your Resume as input and parse the content in JSON format. Share Github Link of the solution if possible.
## Solution:
### Prompt:

    "I will be giving you all the text of my resume. I want you to parse the content of my resume into JSON format. Extract each 
    and every possible information that you can extract and store them in key value pairs in a structured format!   

    Resume Content:
    Komal Pasumarthy
    LinkedIn: linkedin.com/in/komal-pasumarthy/
    Email: pasumarthykomal@gmail.com
    GitHub: github.com/komalpasumarthy
    Mobile: +91 8688602431
    Technical Skills
    Languages: Python, JavaScript
    Technologies: HTML, CSS, JavaScript, Node JS, Express JS, Reach JS, Git, SQLite
    Platforms/Frameworks: Power BI, GitHub, Ubuntu, pandas, numpy, matplotlib, seaborn, scikit-learn, spacy
    Soft Skills: Problem-solving, Leadership, Adaptable, Time Management, Interpersonal
    Projects
    Telecom Customer Churn
    Jun. 2024
    
    Developed a machine learning model to predict telecom customer churn using Logistic Regression and Decision Tree algorithms with hyperparameter tuning. Achieved an 80% accuracy in predicting customer churn.
    GitHub Repository Link: Telecom Customer Churn
    Car Price Prediction
    Mar. 2024
    
    Developed a machine learning model to predict car prices based on various attributes using Recursive Feature Elimination and Manual Feature Selection with logistic regression. Achieved 89.17% and 86.51% test accuracy using the respective feature selection methods.
    GitHub Repository Link: Car Price Prediction
    Power BI Dashboard (Real Mart Sales visualization)
    Jan. 2024
    
    Created a dynamic dashboard to visualize sales data of an E-commerce company. Developed a Power BI dashboard using slicers to enhance data insights and interactivity. Demonstrated proficiency in Power BI with an interactive and insightful dashboard.
    Project Link: Komal Data Visualization Project
    Spotify Data Analysis
    Sep. 2023
    
    Extracted valuable insights from a dataset of over 10,000 songs. Performed data cleaning and visualization to analyze the song data. Gained meaningful information and trends from the Spotify song dataset.
    GitHub Repository Link: Spotify Data Analysis
    Certifications
    Postman API Fundamentals Student Expert Program | Postman (Jan 2024)
    Complete Data Science and Machine Learning | Geeks For Geeks (Jan 2023)
    Full Stack Industry Ready Certification (Ongoing) | NxtWave (Mar 2022)
    Achievements
    Raised sponsorship of Rs.80K+ to conduct 5+ events engaging 1000+ students.
    Finalist in 36hr hackathon gateway for SIH2023.
    Led a Team of 80+ as Vice President of an 8+ Year old student organization.
    Finalist of Fly High Challenge by NxtWave held for 12 weeks.
    Education
    Lovely Professional University, Jalandhar, Punjab
    Bachelor of Technology in Computer Science; CGPA: 8.20
    Aug. 2021 – Present
    
    Sarada Educational Institution, Vijayawada, Andhra Pradesh
    Intermediate; CGPA: 9.23
    Jun. 2019 – Mar. 2021
    
    Sri Somnadha Green Fields Public School, Eluru, Andhra Pradesh
    Matriculation; CGPA: 8.38
    Apr. 2018 – Mar. 2019
    "
### Response 1:
    {
      "name": "Komal Pasumarthy",
      "contact_information": {
        "LinkedIn": "linkedin.com/in/komal-pasumarthy/",
        "email": "pasumarthykomal@gmail.com",
        "GitHub": "github.com/komalpasumarthy",
        "mobile": "+91 8688602431"
      },
      "technical_skills": {
        "languages": ["Python", "Javascript"],
        "technologies": ["HTML", "CSS", "Javascript", "Node JS", "Express JS", "React JS", "Git", "SQLite"],
        "platforms_frameworks": ["Power BI", "GitHub", "Ubuntu", "pandas", "numpy", "matplotlib", "seaborn", "scikit-learn", "spacy"],
        "soft_skills": ["Problem-solving", "Leadership", "Adaptable", "Time Management", "Interpersonal"]
      },
      "projects": [
        {
          "name": "Telecom Customer Churn",
          "technologies": ["Python", "Machine Learning", "Data Analysis"],
          "date": "Jun. 2024",
          "description": [
            "Developed a machine learning model to predict telecom customer churn.",
            "Employed Logistic Regression and Decision Tree algorithms with hyperparameter tuning.",
            "Achieved an 80% accuracy in predicting customer churn."
          ],
          "repository_link": "github.com/komalpasumarthy/Telecom-customer-churn"
        },
        {
          "name": "Car Price Prediction",
          "technologies": ["Python", "Machine Learning", "Data Analysis"],
          "date": "Mar. 2024",
          "description": [
            "Developed a machine learning model to predict car prices based on various attributes.",
            "Utilized Recursive Feature Elimination and Manual Feature Selection with logistic regression.",
            "Achieved 89.17% and 86.51% test accuracy using the respective feature selection methods."
          ],
          "repository_link": "github.com/komalpasumarthy/canPricePredictionUsingMLR-RFEMethod"
        },
        {
          "name": "Power BI Dashboard (Real Mart Sales visualization)",
          "technologies": ["Power BI", "Data Visualization"],
          "date": "Jan. 2024",
          "description": [
            "Created a dynamic dashboard to visualize sales data of an E-commerce company.",
            "Developed a Power BI dashboard using slicers to enhance data insights and interactivity.",
            "Demonstrated proficiency in Power BI with an interactive and insightful dashboard."
          ],
          "project_link": "bit.ly/KomalDataVisualizationProject"
        },
        {
          "name": "Spotify Data Analysis",
          "technologies": ["Python3", "Data Analysis"],
          "date": "Sep. 2023",
          "description": [
            "Extracted valuable insights from a dataset of over 10,000 songs.",
            "Performed data cleaning and visualization to analyze the song data.",
            "Gained meaningful information and trends from the Spotify song dataset."
          ],
          "repository_link": "https://github.com/komalpasumarthy/SpotifyEDAProject"
        }
      ],
      "certifications": [
        {
          "name": "Postman API Fundamentals Student Expert Program",
          "issuer": "Postman",
          "date": "Jan. 2024"
        },
        {
          "name": "Complete Data Science and Machine Learning",
          "issuer": "Geeks For Geeks",
          "date": "Jan. 2023"
        },
        {
          "name": "Full Stack Industry Ready Certification",
          "issuer": "NxtWave",
          "date": "Mar. 2022",
          "status": "Ongoing"
        }
      ],
      "achievements": [
        "Raised sponsorship of Rs.80K+ to conduct 5+ events engaging 1000+ students.",
        "Finalist in 36hr hackathon gateway for SIH2023.",
        "Led a Team of 80+ as Vice President of an 8+ Year old student organization.",
        "Finalist of Fly High Challenge by NxtWave held for 12 weeks"
      ],
      "education": [
        {
          "institution": "Lovely Professional University",
          "location": "Jalandhar, Punjab",
          "degree": "Bachelor of Technology in Computer Science",
          "CGPA": "8.20",
          "date": "Aug. 2021 – Present"
        },
        {
          "institution": "Sarada Educational institution",
          "location": "Vijayawada, Andhra Pradesh",
          "degree": "Intermediate",
          "CGPA": "9.23",
          "date": "Jun. 2019 – Mar. 2021"
        },
        {
          "institution": "Sri Somnadha Green Fields Public School",
          "location": "Eluru, Andhra Pradesh",
          "degree": "Matriculation",
          "CGPA": "8.38",
          "date": "Apr. 2018 – Mar. 2019"
        }
      ]
    }
### Prompt 2:
     Can you change locations into city and state and i want you to read through my resume and provide them sutiable key names 
     also let me know of any other ways which you think the output can be imporved
### Response 2:
    {
      "name": "Komal Pasumarthy",
      "contact_information": {
        "linkedin": "linkedin.com/in/komal-pasumarthy/",
        "email": "pasumarthykomal@gmail.com",
        "github": "github.com/komalpasumarthy",
        "mobile": "+91 8688602431"
      },
      "technical_skills": {
        "languages": ["Python", "JavaScript"],
        "technologies": ["HTML", "CSS", "JavaScript", "Node.js", "Express.js", "React.js", "Git", "SQLite"],
        "platforms_and_frameworks": ["Power BI", "GitHub", "Ubuntu", "pandas", "numpy", "matplotlib", "seaborn", "scikit-learn", "spacy"],
        "soft_skills": ["Problem-solving", "Leadership", "Adaptability", "Time Management", "Interpersonal"]
      },
      "projects": [
        {
          "title": "Telecom Customer Churn",
          "technologies": ["Python", "Machine Learning", "Data Analysis"],
          "completion_date": "Jun 2024",
          "description": [
            "Developed a machine learning model to predict telecom customer churn.",
            "Employed Logistic Regression and Decision Tree algorithms with hyperparameter tuning.",
            "Achieved an 80% accuracy in predicting customer churn."
          ],
          "repository_url": "https://github.com/komalpasumarthy/Telecom-customer-churn"
        },
        {
          "title": "Car Price Prediction",
          "technologies": ["Python", "Machine Learning", "Data Analysis"],
          "completion_date": "Mar 2024",
          "description": [
            "Developed a machine learning model to predict car prices based on various attributes.",
            "Utilized Recursive Feature Elimination and Manual Feature Selection with logistic regression.",
            "Achieved 89.17% and 86.51% test accuracy using the respective feature selection methods."
          ],
          "repository_url": "https://github.com/komalpasumarthy/carPricePredictionUsingMLR-RFEMethod"
        },
        {
          "title": "Power BI Dashboard (Real Mart Sales visualization)",
          "technologies": ["Power BI", "Data Visualization"],
          "completion_date": "Jan 2024",
          "description": [
            "Created a dynamic dashboard to visualize sales data of an E-commerce company.",
            "Developed a Power BI dashboard using slicers to enhance data insights and interactivity.",
            "Demonstrated proficiency in Power BI with an interactive and insightful dashboard."
          ],
          "project_url": "https://bit.ly/KomalDataVisualizationProject"
        },
        {
          "title": "Spotify Data Analysis",
          "technologies": ["Python", "Data Analysis"],
          "completion_date": "Sep 2023",
          "description": [
            "Extracted valuable insights from a dataset of over 10,000 songs.",
            "Performed data cleaning and visualization to analyze the song data.",
            "Gained meaningful information and trends from the Spotify song dataset."
          ],
          "repository_url": "https://github.com/komalpasumarthy/SpotifyEDAProject"
        }
      ],
      "certifications": [
        {
          "title": "Postman API Fundamentals Student Expert Program",
          "issuer": "Postman",
          "issue_date": "Jan 2024"
        },
        {
          "title": "Complete Data Science and Machine Learning",
          "issuer": "Geeks For Geeks",
          "issue_date": "Jan 2023"
        },
        {
          "title": "Full Stack Industry Ready Certification",
          "issuer": "NxtWave",
          "issue_date": "Mar 2022",
          "status": "Ongoing"
        }
      ],
      "achievements": [
        "Raised sponsorship of Rs.80K+ to conduct 5+ events engaging 1000+ students.",
        "Finalist in 36-hour hackathon gateway for SIH2023.",
        "Led a team of 80+ as Vice President of an 8+ year-old student organization.",
        "Finalist in the Fly High Challenge by NxtWave held for 12 weeks."
      ],
      "education": [
        {
          "institution": "Lovely Professional University",
          "city": "Jalandhar",
          "state": "Punjab",
          "degree": "Bachelor of Technology in Computer Science",
          "cgpa": "8.20",
          "duration": "Aug 2021 – Present"
        },
        {
          "institution": "Sarada Educational Institution",
          "city": "Vijayawada",
          "state": "Andhra Pradesh",
          "degree": "Intermediate",
          "cgpa": "9.23",
          "duration": "Jun 2019 – Mar 2021"
        },
        {
          "institution": "Sri Somnadha Green Fields Public School",
          "city": "Eluru",
          "state": "Andhra Pradesh",
          "degree": "Matriculation",
          "cgpa": "8.38",
          "duration": "Apr 2018 – Mar 2019"
        }
      ]
    }


    Suggestions for Improvement:
    Link Formatting: Added "https://" to URLs to ensure they are clickable.
    Date Formatting: Changed date formats for consistency.
    Description Detail: Broke down descriptions into bullet points for clarity.
    Key Names: Used descriptive key names for better readability.
    Consistency: Standardized terminology and capitalization.
    Let me know if you need further adjustments or additional information!

## Prompts Summary:
### Prompt1: I will be giving you all the text of my resume. I want you to parse the content of my resume into JSON format. Extract each and every possible information that you can extract and store them in key value pairs in a structured format!
### Prompt2: Can you change locations into city and state and i want you to read through my resume and provide them sutiable key names also let me know of any other ways which you think the output can be imporved

# Explanation: 
### Prompt1: In this prompt I simply let the GPT know what it has to do and how it has to do and what is the input i was going to give
### Prompt2: In this prompt I examined the GPT Output and let it know what could be the potential changes and asked it for prtential improvements in the output given by it guiding it iteratively to achive desired output
