# Optimizing IT Support Team Performance Using Analytics

##  🔹Problem Statement

   Customer support teams manage thousands of service tickets daily, making it difficult to monitor response efficiency, identify recurring issues, and maintain service quality.
This project analyzes customer support ticket data to evaluate operational performance, identify problem sources, and provide actionable insights for improving support efficiency and customer experience.

Organizations often lack visibility into:

   ->How quickly support teams respond to customers

   ->Which issues generate the highest workload

   ->Products or channels causing operational delays
   
This project aims to:

  -> Measure support performance using key KPIs

  ->Identify recurring issue patterns

  -> Support data-driven decision making
  
## 🔹 Dataset Description

   Dataset: Customer Support Ticket 
   
   Source: Kaggle
   
The Customer Support Ticket Dataset is a dataset that includes customer support tickets for various tech products. It consists of customer inquiries related to hardware issues, software bugs, network problems, account access, data loss, and other support topics. The dataset provides information about the customer, the product purchased, the ticket type, the ticket channel, the ticket status, and other relevant details.

 Features Description
 
   Ticket ID: A unique identifier for each ticket.
   
   Customer Name: The name of the customer who raised the ticket.
   
   Customer Email: The email address of the customer.
   
   Customer Age: The age of the customer.
   
   Customer Gender: The gender of the customer.
   
   Product Purchased: The tech product purchased by the customer.
   
   Date of Purchase: The date when the product was purchased.
   
   Ticket Type: The type of ticket (e.g., technical issue, billing inquiry, product inquiry).
   
   Ticket Subject: The subject/topic of the ticket.
   
   Ticket Description: The description of the customer's issue or inquiry.
   
   Ticket Status: The status of the ticket (e.g., open, closed, pending customer response).
   
   Resolution: The resolution or solution provided for closed tickets.
   
   Ticket Priority: The priority level assigned to the ticket (e.g., low, medium, high, critical).
   
   Ticket Channel: The channel through which the ticket was raised (e.g., email, phone, chat, social media).
   
   First Response Time: The time taken to provide the first response to the customer.
   
   Time to Resolution: The time taken to resolve the ticket.
   
   Customer Satisfaction Rating: The customer's satisfaction rating for closed tickets (on a scale of 1 to 5).


## 🔹 Key Performance Indicators (KPIs)

The following KPIs were used to evaluate and optimize support performance:

  ->Total Number of Tickets : The total count of all support requests submitted by customers.

  ->Average First Response Time : The average time a customer waits before receiving their very first reply from a support agent.

  ->Average Response Time : The average time taken by agents to reply to customer messages throughout the duration of a ticket.

  ->High  Priority Ticket : The count of urgent issues that require immediate attention to prevent major customer dissatisfaction.

  ->Tickets per Customer : The average number of times a single customer has reached out for support, indicating how often they face issues.


   
## 🔹 Dashboard

 Dashboard 1:
 
   This dashboard gives a quick snapshot of the support team’s work.We can see how many tickets there are, how urgent they are, and which products are causing the most issues.
   
   KPI Cards (Total Tickets, Avg Response Time ,Avg First Response Time) : Used to give the big picture numbers immediately.

   Ticket Volume Distribution : A pie chart is used here to show the share of the workload based on priority.

   Channel Distribution : The donut chart effectively shows the breakdown of communication methods (Email, Chat, Phone).

   Response Time Trend : Line chart shows whether the team is getting faster or slower at responding over the months.

   Top 10 Products Generating Tickets : Bar chart ranks products by volume
   
   Total Tickets by Gender : Pie chart is a simple split that shows the gender of the customers raising tickets.

   Top 10 Most Reported Issues: Column charts are perfect for comparing different categories side by side.
   
   Ticket Volume by Age Group : Column chart ,by grouping ages (e.g., 20s, 30s, 40s), this chart identifies which generation is contacting support the most.

   Dashboard 2 :
   
 It is designed to dig into the data to find exactly why customers are complaining and which specific product issue combinations are creating the most risk for the company.

   KPI Cards (High Priority Tickets, Tickets per Customer) : Used to give the big picture numbers immediately.

   Total Tickets by Subject and Ticket Priority : Bar chart shows not just what the issues are, but how dangerous they are.

   Total Tickets by Product and Ticket Type : Bar chart groups different types of problems for each product side by side.

   Total Tickets by Month and Year : A line chart tracks trends over time.
     
   
  
## 🔹 Key Insights

   ->The GoPro Hero has the highest ticket volume.
   
   ->Software Bugs are the #1 ticket subject, and they are also marked as Critical.

   ->Ticket volume is spread across all age groups.
   
   ->The Tickets per Customer KPI is high.

   ->25% of our total volume is Critical.


## 🔹 Tools Used

  Python – Data cleaning and exploratory data analysis
  
  Pandas & NumPy – Data manipulation and preprocessing
  
  Power BI – Interactive dashboard creation and KPI visualization
