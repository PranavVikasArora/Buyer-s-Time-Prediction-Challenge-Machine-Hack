# Buyer-s-Time-Prediction-Challenge-Machine-Hack
Competition link: https://www.machinehack.com/hackathons/buyers_time_prediction_challenge/overview
Buyers spend a significant amount of time surfing an e-commerce store, since the pandemic the e-commerce has seen a boom in the number of users across the domains. In the meantime, the store owners are also planning to attract customers using various algorithms to leverage customer behavior patterns

Tracking customer activity is also a great way of understanding customer behavior and figuring out what can actually be done to serve them better. Machine learning and AI has already played a significant role in designing various recommendation engines to lure customers by predicting their buying patterns

In this competition provided the visitor's session data, we are challenging the Machinehack community to come up with a regression algorithm to predict the time a buyer will spend on the platform.

 
Dataset Description:
Train.json - 5429 rows x 9 columns (Includes time_spent Column as Target variable)
Test.json - 2327 rows x 8 columns
Sample Submission.csv - Please check the Evaluation section for more details on how to generate a valid submission
 
Attribute Description:
session_id - Unique identifier for every row
session_number - Session type identifier
client_agent - Client-side software details
device_details -  Client-side device details
date - Datestamp of the session
purchased - Binary value for any purchase done
added_in_cart - Binary value for cart activity
checked_out -  Binary value for checking out successfully
time_spent - Total time spent in seconds (Target Column)

Special Thanks to Som Nath Ghosh for his guidance through out this project, and for teaching me many new concepts which have been used to build this model. Som Nath Ghosh's Github : https://github.com/Som-Nath-Ghosh
