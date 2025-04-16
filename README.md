# Empowering Dreams: Strengthening ROSCAs for Micro-Businesses in Rural Africa!
# Assessing the Impact of Informal Lending Networks on Micro-Business Sustainability
# Situation
ROSCAs are a lifeline for micro-business owners in rural Africa, but they’re not working well enough! Imagine small shop owners in places like Bungoma, struggling to grow because loans are hard to repay. In this project, we analyzed data from  1000 micro-business owners, where 283 are at risk of failing due to big groups and tough repayment rules. We’ll uncover why large groups, weekly payments, and loan misuse affects ROSCAs and how to help them thrive.
# Task
As a data analyst, my job was to find out why ROSCAs are failing micro-businesses and fix it. I needed to check things like group size, repayment schedules, and how loans are used to spot businesses in danger. I worked with my team for 2 weeks to finish this project. Our goals were to find the big problems, build a prediction system to catch risks early, help ROSCA leaders act fast, and send support to the neediest businesses.
# Action
I started by pulling data from our table, [MicroBusiness].[dbo].[Cleaned dataset roscas]. Using SQL Server, I cleaned it up by fixing missing numbers and removed duplicates to make it ready. Then, I analyzed it with SQL to find patterns, like why 65% of businesses in large groups struggle to repay or 50% use loans for emergencies, not growth. I used Python to build a linear regression model, predicting which businesses are at risk based on group size and repayment frequency. Finally, I created a clear dashboard in Power BI to show the crisis. Check out the dashboard preview below!
![Image](https://github.com/user-attachments/assets/fa3b05bc-bddc-43a7-b612-8f3474790a3a)
# Results
- Total Businesses: 1000 micro-business owners in ROSCA groups, with 300 (35%) at high risk of failing.
- Group Size Problem: 65% of businesses in large groups (21-29 members) face repayment issues ,too many people hence too hard to manage.
- Repayment Stress: 70% of businesses with weekly repayments struggle, compared to 30% with monthly repayments.
- Loan Misuse: 50% use loans for emergencies (like sickness), not business growth leaving them stuck.
- Experience Matters:
  - New members (1-3 years in ROSCA) and startups (1-3 years in business) have the lowest sustainability scores (average: 4.2/10).
  - Long-term members (7-9 years) and mature businesses (15-20 years) score highest (average: 8.1/10).
- Borrower Age Impact: Young adults (18-29 years) face more challenges and 60% miss repayments due to inexperience.
- Prediction System: Our model flags 300 businesses at risk, especially startups in large groups with weekly repayments
# Recommendations
# Main Recommendations for Solving the Problem:
- Keep ROSCA groups small (5-10 members) to boost trust by spliting large groups into smaller ones now.
- Switch to monthly repayments for 70% struggling with weekly schedules to ease stress.
- Teach 50% of members to use loans for business growth like buying more goods and not emergencies.
- Use our prediction system to spot 300 at-risk businesses early and give them smaller loans or extra time to pay.
- Partner with NGOs to train young adults (18-29 years) on money skills, helping 60% repay on time.
# Reflection
This project showed me the power of teamwork ,we shared tasks to meet our 2 weeks  deadline. I learned to listen to ROSCA leaders, who wanted simple tools like our prediction system, making our dashboard a real game-changer. Together, we found big gaps like 65% of large groups struggling and real fixes. I improved my SQL, Python, and Power BI skills, but most of all, I’m excited to keep helping micro-business owners grow strong and make their communities proud!
