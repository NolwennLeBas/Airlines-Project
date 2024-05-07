# Airlines-Project

The airline reviews dataset (Airlines2.csv) is collected from the website: https://www.airlinequality.com/review-pages/a-z-airline-reviews/

The methodology of its collection is published in https://github.com/Juhibhojani/Airline-Reviews-

The features in the dataset are listed below

 - Airline Name
 - Overall Rating
 - Review Title
 - Review Date
 - Verified (whether the review is verified or not)
 - Review
 - Aircraft
 - Type of Traveller
 - Seat Type
 - Route
 - Date Flown
 - Seat Comfort
 - Cabin Staff Service
 - Food & Beverages*
 - Ground Service
 - Inflight Entertainment
 - Wifi & Connectivity
 - Value for Money
 - Recommended

The goal of this project is to gain valuable insights into customer experiences with various airlines. To achieve this I'll build a model to predict Overall Rating given by a customer and perform time series analysis and EDA to uncover hidden patterns and make data-driven decisions to enhance the overall airline experience.

The jupyter notebooks will be focused on building a regression model and creating a MySQL database while the graphical presentations can be found in this Tableau workbook: https://public.tableau.com/views/AirlinesProject_17146458470170/TOP_Airlines?:language=fr-FR&:sid=&:display_count=n&:origin=viz_share_link

Note: Some issues arised due to how the website rating system is structured. Indeed, some parameters are measured on different scales: 
- Recommended status measured on the binary 'yes/no' scale
- Overall Rating score for the flight measured on the numeric scale of 1 to 10
- Individual quality parameters (Seat Comfort, Cabin Staff Service, Food and Beverages, Ground Service, Inflight Entertainment, Wifi and Connectivity, and Value for Money) are measured on a scale of 1 to 5
This resulted in some confusive reviews with customers recommending airlines while giving them a low Overall Rating and vice versa.
