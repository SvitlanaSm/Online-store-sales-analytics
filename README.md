# Online-store-sales-analytics
📌 **Project Overview**  
This project is focused on analyzing user session data collected from a web platform using tools such as Google Analytics. The dataset includes information about user devices, geographic location, session details, product views, and more. The goal is to gain actionable insights about user behavior, content performance, and marketing effectiveness.  

✅ Platform: SQL, Google Colab, Tabeau
📂 Dataset size: 349,545 rows × 18 columns

🎯 **Objectives**  
* Explore and clean web session data  

* Understand user distribution by geography, device, and traffic source  

* Analyze product views and pricing patterns  

* Segment users based on subscription and verification status  

* Visualize behavioral trends using Python data tools  

📁 **Dataset Description**  
The dataset contains anonymized web session data. Each row represents a single user interaction (session).

🔍 **Column Descriptions**  

`date`	- Date of the session  
`ga_session_id` -	Unique session identifier  
`continent` -	Continent from which the visit originated  
`country` -	Country of the user  
`device` -	Type of device (e.g., desktop, mobile, tablet)  
`browser` -	Browser used during the session  
`mobile_model_name` -	Mobile device model (applicable only for mobile traffic)  
`operating_system` -	Operating system of the device  
`language` -	Browser language settings of the user  
`medium` -	Type of traffic source (e.g., organic, referral, cpc)  
`channel` -	Marketing channel (e.g., Direct, Organic Search, Social)  
`account_id` -	User’s account identifier  
`is_verified` -	Whether the account is verified (1 = yes, 0 = no)  
`is_unsubscribed` -	Whether the user unsubscribed from emails (1 = yes, 0 = no)  
`category` -	Product or service category viewed  
`name` -	Name of the product or service  
`price` -	Price of the product or service  
`short_description` -	Short description of the product or service  

📊 **Key Analyses** (suggested/notebook-dependent)  
* Most common countries and devices used by users  

* Price distributions across product categories  

* Subscription and verification breakdown by user segment  

* Peak user activity by date or channel  

* Correlation analysis between price and engagement metrics

📌 **Project Goals**
This project serves as a portfolio demonstration of:  

* Working with real-world web analytics data

* Cleaning and transforming large datasets

* Creating visual insights for marketing teams

* Building reports that can drive business strategy
