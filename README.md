# Hotel-Booking-Analysis-Capstone-Project-EDA- 
This project is a Exploratory Data Analysis(EDA) of a booking dataset of two hotels that are City hotel and Resort hotel.
This dataset contains 119390 Rows and 32 Columns. And 31994 dublicate rows so after removing all duplicate rows the shape of dataset became 87396 rows & 32 columns. The null values are in some columns like country,company,agent and children so i filled null/missing values by 'other' for country column and by 'zero' for remaining ones.

The data types of columns are object,int64,float64. I added two new columns named 'total people' by adding adult,children and babbies column data and second column is 'total_stay' by adding stays_in_weekend_nights and stays_in_week_nights.

This project have 15 charts. These charts contains analysis and visualization of some important factors that are mentioned below.
* Number of bookings in both type of hotels.
* Which agent made maximum bookings.
* Percentage of repeated guests.
* Cancellation percentage of bookings.
* Percentage of Customer Type.
* Percentage of requirement for car parking space of guest.
* Percentage for preference of deposite type

**Some Bivariate analysis and Multivariate analysis**

* What kind of food was liked by guests.
* From which country maximum people came.
* Most preferred room type by the customers.
* Which month got maximum bookings.
* Which Distribution channel was mostly used for hotel bookings.
* In which year higest bookings occurs.
* Correlation of the columns by Heatmap.
* The Optimal stay length in both types of hotels. 

For visualization i used different types of graph like barplot,piechart,countplot,lineplot,heat map.
