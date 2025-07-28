# IAC_DATA_ANALYTICS
ABSENCE OF INSIGHTS FOR THE RELATIONSHIP BETWEEN STUDENT'S ECONOMIC BACKGROUND, ACADEMIC PERFORMANCE, COMPETENCE & EXPECTED SALARY.
This repository contains the data analysis project for the client, focusing on deriving actionable insights from their event attendee data. The project analyzes student demographics, academic performance, and career aspirations to help optimize marketing strategies and enhance event offerings.

Table of Contents
Project Overview

Problem Statement

Project Objectives

Dataset

Methodology

Key Findings

Tools and Technologies

How to Use

Future Scope

Project Overview
The client is an organization dedicated to enhancing student skills through various professional development events. While successful in attracting thousands of attendees, their marketing and content strategies have been largely based on intuition. This project was initiated to leverage their rich dataset of attendee information to transition towards a data-driven decision-making model. By analyzing the relationships between student academics, event participation, and career goals, this project provides the insights needed to refine their strategy and better serve their community.

Problem Statement
The client's primary business problem was a lack of data-driven insights to guide their strategic decisions. They were unable to definitively identify which marketing channels provided the best return on investment or fully understand the profiles of their attendees. This ambiguity made it difficult to allocate marketing budgets effectively and to tailor event content to the specific needs and career aspirations of their audience, hindering their potential for strategic growth.

Project Objectives
The primary objective was to analyze historical attendee data to derive actionable insights that would optimize marketing strategies and guide future content development. The specific goals were:

Analyze Event Performance: Identify the most popular events to understand which topics resonate most with the target audience.

Evaluate Marketing Channel Effectiveness: Determine the most successful channels for attracting participants to focus marketing spend.

Develop Attendee Profiles: Create detailed profiles of attendees by analyzing their demographics, academic background, and professional aspirations.

Provide Data-Driven Recommendations: Translate the findings into a clear set of strategic recommendations to guide future business decisions.

Dataset
The analysis was performed on a cleaned dataset (Cleaned_All Events Data.csv) containing registration information for over 1,500 attendees across various events. The key fields in the dataset include:

Events: The name of the event attended.

College Name: The attendee's college or institution.

Year of Graduation: The attendee's graduation year.

CGPA: The attendee's Cumulative Grade Point Average.

City: The attendee's city of residence.

How did you come to know about this event?: The marketing channel source.

Expected salary (Lac): The attendee's salary expectation.

Leadership- skills: A self-assessed leadership score.

Methodology
A structured, multi-stage approach was adopted to ensure the findings were accurate and strategically relevant:

Discovery and Objective Setting: The project began by defining the client's business challenges and setting clear analytical objectives.

Data Preparation: The raw data was rigorously cleaned, validated, and standardized to create a reliable foundation for analysis.

Exploratory Data Analysis (EDA): An initial exploration was conducted to identify high-level patterns and trends in the data.

Focused Analysis: A deep-dive analysis was performed to uncover the relationships between student academics, career goals, and event participation.

Synthesis and Recommendation: The findings were synthesized into a cohesive narrative, and a set of actionable recommendations was formulated.

Key Findings
The analysis yielded several key insights:

Most Popular Events: The "Internship Program(IP) Success Conclave" and "Art of Resume Building" were the most attended events, indicating a strong interest in direct career preparation.

Top Marketing Channels: "WhatsApp," "Email," and "College Referrals (SPOC)" were the most effective channels for attracting attendees.

Geographic Hubs: A significant number of attendees came from major educational hubs like Mumbai, Nagpur, and Pune.

Career Aspirations: A strong correlation was found between higher CGPAs and higher salary expectations, suggesting that academic performance is a key indicator of career ambition among the attendees.

Tools and Technologies
Data Cleaning and Analysis: Python (with libraries such as Pandas and NumPy)

Data Visualization: Matplotlib, Seaborn, and Power BI

Reporting: Microsoft Word and Markdown

How to Use
To replicate this analysis, follow these steps:

Clone the repository:

git clone https://github.com/your-username/student-engagement-analysis.git


Install the required libraries:

pip install pandas numpy matplotlib seaborn


Run the analysis script:

Place the Cleaned_All Events Data.csv file in the data directory.

Execute the main analysis script (e.g., analysis.ipynb or analysis.py).

Future Scope
This project serves as a strong foundation for future data-driven initiatives. Potential next steps include:

Predictive Modeling: Building a model to predict which students are most likely to attend future events.

Longitudinal Analysis: Tracking attendees post-event to measure the real-world impact of the courses on their career success.

Enhanced Data Collection: Refining the data collection process to include more granular details like academic majors for deeper segmentation.

Automated Reporting: Implementing a live dashboard that updates in real-time with new registration data.
