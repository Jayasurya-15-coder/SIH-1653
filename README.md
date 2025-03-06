# Smart India Hackathon Workshop
# Date: 
## Register Number: 212224100026
## Name: JAYASURYA B
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea

## 1. Platform Development
### a. User Interface
Dashboard for Interviewers: A user-friendly interface where interviewers can access candidate profiles, interview questions, and scoring metrics.
Candidate Portal: A separate interface for candidates to view their interview schedule, prepare for questions, and access feedback post-interview.
### b. Virtual Board Room Environment
Video Conferencing: Integrate a video conferencing tool that allows for face-to-face interaction, simulating a real Board Room experience.
Screen Sharing: Enable interviewers to share presentations or documents relevant to the interview.
## 2. Question Bank Creation
### a. Ice-Breaking Questions
Develop a set of initial questions aimed at easing candidates into the interview. These could include personal interests, career aspirations, and motivations for applying.
### b. Techno-Managerial Questions
Create a categorized question bank based on different expertise areas (e.g., engineering, project management, research).
Questions should range from basic to advanced levels, depending on the candidate's experience and the position applied for.
### c. Dynamic Question Selection
Implement an algorithm that selects questions based on the candidate's profile, ensuring relevance to their expertise and the job requirements.
### 3.  Overall Scoring and Feedback
## a. Aggregate Scoring
Calculate an overall score for each candidate based on the relevancy of questions asked and the quality of their responses.
Provide a breakdown of scores in different categories (e.g., technical knowledge, managerial skills, communication).
## b. Feedback Mechanism
After the interview, generate a feedback report for candidates, highlighting strengths and areas for improvement.
Allow interviewers to provide qualitative feedback alongside quantitative scores.
### 4. Scoring Mechanism
## a. Question Relevancy Scoring
Develop a scoring system for interviewers to rate the relevancy of each question to the candidate's expertise on a scale (e.g., 1-5).
Use machine learning to analyze past interviews and refine the question bank based on effectiveness.
## b. Candidate Response Evaluation
Create a rubric for interviewers to evaluate candidate responses based on clarity, depth of knowledge, and relevance to the question asked.
Implement a scoring system (e.g., 1-5) for each response, allowing for quantitative assessment.


## Proposed Solution / Architecture Diagram

![Screenshot 2025-03-06 184724](https://github.com/user-attachments/assets/5bb57895-43e5-480e-a6c2-739dc95d88d0)


## Use Cases

![Screenshot 2025-03-06 204943](https://github.com/user-attachments/assets/26f047a6-435e-4ec6-abd5-0947f4e0a78c)


## Technology Stack

### 1. Front-End Technologies
-> HTML5/CSS3: For structuring and styling the web application.
-> JavaScript Frameworks:
     => React.js or Angular: For building a dynamic and responsive user interface.
     => Redux (if using React): For state management.
-> Bootstrap or Material-UI: For responsive design and pre-built UI components. 

### 2. Back-End Technologies
-> Node.js: For building the server-side application, allowing for asynchronous processing and scalability.
-> Express.js: A web application framework for Node.js to handle routing and middleware.
-> Python (optional): For implementing machine learning algorithms for question relevancy scoring and response evaluation.

### 3. Database Technologies
-> Relational Database:
    PostgreSQL or MySQL: For structured data storage, such as user profiles, interview questions, and scores.
-> NoSQL Database (optional):
    MongoDB: For storing unstructured data, such as feedback and logs.
## Dependencies

### 1. Front-End Dependencies
a. Core Libraries
-> React.js (or Angular)
-> Redux (if using React)
### 2. Back-End Dependencies
a. Core Libraries
-> Node.js and Express.js
b. Database Libraries
-> PostgreSQL or MySQL
### 3. Video Conferencing Dependencies
-> WebRTC
-> Third-Party APIs

