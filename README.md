# Instahyre Job Analytics

![image](https://github.com/bhardwaj-priya7/Instahyre_Job_Analysis/assets/138392873/717fa0a1-72bd-4342-b52e-0ebe0a94d277)


## Project Overview
Welcome to the Instahyre Job Analytics repository! This project offers insightful analysis and visualization of the job market trends, gathered through web scraping and data analysis.

### Team Members
- Priya Bhardwaj (Myself)
- Amarjeet Roy
- Ajay Kumar
- Bharat Sharma

## Problem Aimed to Solve
The Instahyre Job Analytics project aims to comprehensively understand the job market dynamics using data-driven insights. Our objective is to extract, preprocess, and analyze job posting data from Instahyre and LinkedIn, shedding light on the employment landscape.

## Description of Data Cleaning / Preprocessing
### Data Extraction and Preprocessing
- We utilized the Selenium library to extract job posting data from Instahyre's website.
- The Extraction directory contains the extraction script `Extraction_Code.py` and extracted CSV files.
- The Processing directory features `Data Preprocessing and Clustering.ipynb` for data cleaning and K-means clustering.
- 
### K-means Clustering Model
We used Scikit-learn to build a K-means clustering model. This model categorizes companies based on their LinkedIn followers and employee count, allowing us to understand different company classes. The K-means model helped us gain insights into the job market and classify companies effectively.

![image](https://github.com/bhardwaj-priya7/Instahyre_Job_Analysis/assets/138392873/f7554aa9-c70c-460d-8674-30dbf54537bb)

![image](https://github.com/bhardwaj-priya7/Instahyre_Job_Analysis/assets/138392873/fe5a0840-152a-44c5-9dd8-23054ef5fc6e)



### Interactive Website
- To visualize insights, we built an interactive website using Flask, HTML, and CSS.

- Users can input their skills
![image](https://github.com/bhardwaj-priya7/Instahyre_Job_Analysis/assets/138392873/ef932f6a-6e07-4097-9115-2cd8a739ee27)


- Explore summarized job details
![image](https://github.com/bhardwaj-priya7/Instahyre_Job_Analysis/assets/138392873/42ec6fba-2903-43ff-ba46-265b9465c559)


- Dive into comprehensive job postings.
![image](https://github.com/bhardwaj-priya7/Instahyre_Job_Analysis/assets/138392873/13dc8cf2-7d3d-4b45-b946-ca733b28d783)


- The Application directory houses the website's code, templates, and processed data.

### Some Insights 

![image](https://github.com/bhardwaj-priya7/Instahyre_Job_Analysis/assets/138392873/cb2fd988-51f4-41a8-844a-6c4ebcfe2a32)

![image](https://github.com/bhardwaj-priya7/Instahyre_Job_Analysis/assets/138392873/42ec87fd-65f4-46e2-9589-3fc1fbb7a34c)

### Extraction Directory
- Web scraping code and files related to data extraction.
- `Extraction_Code.py`: Python script for web scraping job posting data and LinkedIn information.
- `Job webLink.csv`: Contains web links of all job pages.
- `merged Data.csv`: Merged data from Instahyre and LinkedIn.
- `New Updated Csv.csv`: Preprocessed data with some initial modifications.

### Processing Directory
- Code and files related to data preprocessing and clustering.
- `Data Preprocessing and Clustering.ipynb`: Jupyter Notebook containing data preprocessing and building the K-means clustering model using Python libraries.
- `Processed_file.csv`: Processed data with class information and details for display on the website.
- `New Updated Csv.csv`: Preprocessed data with some initial modifications.

### Application Directory
- Code for the interactive website.
- `app.py`: Flask application to handle user inputs and serve web pages.
- Templates: Directory containing HTML templates for the website pages.
- `first.html`: Landing page for user input.
- `second.html`: Page displaying summarized job market insights.
- `Job_details.html`: Page showing detailed job posting information.
- `Processed_file.csv`: Processed data with class information and details for display on the website.

## Summary of Limitations/Challenges Faced
- Throughout the project, we encountered challenges related to data quality and complexity.
- The regional focus of the project means that the insights are specific to the chosen area and may not apply universally.
- Time constraints limited the depth of analysis that could be performed.

## Usage
Explore the extracted data and preprocessing steps in the Extraction and Processing directories. Dive into the interactive website in the Application directory, run `app.py`, and visit the local server. Gain insights into job market trends, industry preferences, and job posting details.

## Conclusion

The Instahyre Job Analytics project has successfully provided comprehensive insights into the job market dynamics. Through web scraping, data analysis, and the creation of an interactive website, we've empowered job seekers, professionals, and businesses with valuable information to make informed decisions.

Our journey included data extraction and preprocessing, resulting in a clean and organized dataset. We leveraged K-means clustering to classify job postings and created an interactive website to visualize the data, making it accessible to a wider audience.

The project has equipped users with the ability to explore job market trends, industry preferences, and specific job details, ultimately contributing to better career decisions and informed hiring strategies.

We express our gratitude to the project providers for entrusting us with this opportunity and extend our thanks to our mentors and faculty members for their guidance and support.

## Future Scope

In the future, we aim to expand the capabilities and impact of the Instahyre Job Analytics project:

- **Data Enhancement:** We plan to integrate data from additional job platforms and sources, increasing the depth and breadth of insights.
- **Advanced Analytics:** Exploring predictive modeling and natural language processing techniques to provide more accurate job market forecasts and deeper content analysis.
- **User Experience Improvements:** Enhancing the platform's user interface, introducing mobile applications, and personalization features to tailor the experience for users.
- **Collaboration and Networking:** Introducing user forums, discussion boards, and LinkedIn integration to foster networking and knowledge-sharing among users.
- **Monetization Strategies:** Exploring revenue-generating opportunities through premium features and data services.
- **Data Security and Compliance:** Strengthening data security measures and providing compliance reports for organizations.
- **Continuous Improvement:** Implementing a feedback system for user suggestions and keeping the platform updated with the latest industry trends.

The future of the Instahyre Job Analytics project holds promise for delivering even greater value to job seekers, professionals, and businesses navigating the dynamic job market landscape.


## Acknowledgments
Special thanks to the project providers for entrusting us with this opportunity. We also extend our gratitude to the supportive mentors and faculty members.

Thank you for your interest in the Instahyre Job Analytics project!
