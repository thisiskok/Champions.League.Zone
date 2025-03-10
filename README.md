Notes:
The backend may enter a sleep state after extended inactivity, requiring time to restart and re-establish the database connection when a new request arrives. This can cause an initial request delay of **30 seconds to 2 minutes** and a database connection delay of **10-15 seconds** during reinitialization.

Champions league zone is a comprehensive project designed to scrape match statistics for over 1200 players, manipulate and present the data dynamically, and predict match outcomes using machine learning. The project is divided into four main components: Backend, Frontend and Data Scraping
![image](https://github.com/user-attachments/assets/dda9c68d-2ef4-4cd4-9c21-05b06c51d8fe)
Here is the project: https://champions-league-fronted.vercel.app/

**Features**

**Data Scraping:** Engineered a comprehensive data scraping of match statistics for 1200+ players using Python and pandas.
**Backend:** Dynamic manipulation and presentation of the scraped data through a Spring Boot application.
**Database:** Real-time data manipulation within a Postgres database using SQL queries.
**Frontend:** Seamless integration with a user-friendly ReactJS interface.
