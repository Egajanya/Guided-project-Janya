# Guided-project-Janya
📌 Hotel Booking Cancellation Analysis

📊 Project Overview

This project analyzes hotel booking data to identify patterns and drivers of booking cancellations using Power BI.

⸻

Business Objective

To understand:
	•	What drives booking cancellations
	•	When cancellations occur most
	•	Which customer segments cancel more
	•	How deposit type impacts cancellations


 Data Source

The dataset contains hotel booking records including:
	•	Arrival Date
	•	Country
	•	Market Segment
	•	Deposit Type
	•	Customer Type
	•	Booking Status (is_canceled)


 Data Preprocessing

The following transformations were performed:
	•	Converted arrival_date to Date format
	•	Created Month Number column
	•	Created Month Name column
	•	Sorted Month Name by Month Number
	•	Created DAX measures:
	•	Total Bookings
	•	Total Cancellations
	•	Cancellation Rate


 Analysis Techniques
	•	KPI Cards for high-level metrics
	•	Line chart for trend analysis
	•	Donut chart for market segment contribution
	•	Bar charts for country and booking type analysis
	•	Top N filtering for country

 Dashboard Design Choices
	•	Clean layout with aligned visuals
	•	Minimal color palette
	•	Interactive slicers for filtering
	•	Focused on business interpretation

🔍 Key Insights
	•	Cancellation rate is approximately 40.9%
	•	Peak cancellations occur mid-year
	•	Online TA segment drives highest cancellations
	•	No Deposit bookings have higher cancellation likelihood

 Tools Used
	•	Power BI Desktop
	•	DAX
	•	GitHub for documentation
