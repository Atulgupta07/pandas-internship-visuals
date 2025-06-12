🧠 Project Title:
Visual Analytics Dashboard for Internship Participation Trends at MITS  

🎯 Project Objective
The main goal of this project is to analyze and visualize internship participation trends among students of MITS using JSON-based student offer data. The dashboard provides stakeholders (faculty, training & placement officers, and department heads) with clear, interactive visualizations to make informed decisions on:

Popular and emerging internship domains

Engagement level by college or department

Trends over time (e.g., seasonality of offers)

Domain preferences per academic year

📊 Key Business Questions (KPIs Answered by the Dashboard)
The dashboard answers the following key performance questions:

Which domains are most popular among students for internships?
→ Answered using: Pie Chart and Bar Chart of Domains

Which college or department has the highest internship participation?
→ Answered using: Bar Chart by College

How has internship participation changed over time?
→ Answered using: Line Chart of Offer Dates

What are the trends in internship domain preferences across academic years?
→ Answered using: Static Image Chart (Grouped Bar)

🔧 Data Processing Workflow
Data Format:
Each internship record is in JSON format, containing:

Name, College, Domain, Date, Academic Year

File Upload:
Users can upload a .json file through the dashboard UI.

Data Extraction:

Count how many students selected each domain

Count how many offers came from each college

Group offers by date

Load external chart image showing academic year vs domain preferences

Visualization Tools:

All charts are built using Plotly.js (latest CDN)

Styling follows a glassmorphism theme with icy blue background

📈 Dashboard Visual Insights
1. Pie Chart: Offers by Domain
Helps quickly see what percentage of total offers each domain accounts for.

Example: Web Development may dominate with ~25% of offers.

2. Bar Chart: Number of Offers by Domain
Quantitative comparison across domains.

Identifies top domains like Python Programming, Web Development, or AI/ML.

3. Bar Chart: Offers by College
Visualizes departmental performance in internships.

Useful for cross-departmental benchmarking.

4. Line Chart: Offers Over Time
Shows when students are actively applying/getting internships.

Peaks can indicate active placement months or summer/winter internship seasons.

5. Image Chart: Domain vs Academic Year
Static chart uploaded by the user.

Illustrates how domain interest shifts by year (e.g., 1st-years prefer Web Dev, seniors prefer AI).


🔍 Insights Derived
Web Development, Python, and AI/ML are the most popular internship domains.

3rd and 4th Year students contribute the most to internship participation.

Certain domains (e.g., App Dev, Backend) are preferred more by early-year students.

Internship activity spikes in April–June, possibly due to summer internships.

Some colleges outperform others in student internship engagement.

✅ Conclusion
This interactive dashboard provides a centralized and insightful visual overview of internship trends. By converting raw student internship data into actionable insights, institutions can:

Strategize training programs

Focus on high-demand domains

Identify and support underrepresented colleges or academic years

Track placement seasonality and engagement


