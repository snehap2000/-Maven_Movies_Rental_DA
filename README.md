# Maven_Movies_Rental_DA
Data analysis of movies CD/DVD rental (transactions) and inventory

## Maven Movies Data Analysis: Enhancing Insights for a Rental Business

# Project Overview:
This project analyzes a movie rental business's database to provide actionable insights for improving operations, marketing strategies, and inventory management. The dataset is hosted in the MAVENMOVIES database, and SQL was extensively used for exploratory data analysis (EDA), schema understanding, and answering business-critical ad-hoc queries.

# Project Objectives:

## Customer Insights:
Identify customer details (names, emails) for targeted marketing campaigns. Analyze customer rental patterns to improve customer engagement.

## Movie Inventory Analysis:
Explore the rental inventory and classify movies based on rental rates and availability. Provide recommendations for expanding the movie collection based on popularity and rental rates. Revenue Optimization:

Analyze rental rates to identify trends and the profitability of various pricing categories. Determine the most rented movie categories and ratings to maximize revenue.

## Operational Efficiency:
Help track and manage movie inventory effectively. Highlight gaps in the inventory and optimize stock levels.

## Tools & Library Used

www.mysql.com

![image](https://github.com/user-attachments/assets/eccd0ac1-e743-45df-b97b-0d244b74bf03)


Data Schema:

![Screenshot 2025-01-06 165754](https://github.com/user-attachments/assets/615a5718-34fa-4653-900a-dbde6aa0cc28)




## Query Task

 1.How can we extract the first name, last name, and email address of all customers to prepare a comprehensive contact list for the marketing team?


![Screenshot 2025-01-06 154615](https://github.com/user-attachments/assets/47f8f4dd-9ae5-4848-b7a0-f8a0a5660a4c)


 2.What is the total number of movies in the inventory that are available for rent at the lowest rental rate of $0.99?


![Screenshot 2025-01-06 154636](https://github.com/user-attachments/assets/82f8b7fc-1713-4734-aac4-d50702f4c305)
 

 3.How can we categorize all movies based on their rental rates and determine the count of movies in each category?


 ![Screenshot 2025-01-06 154650](https://github.com/user-attachments/assets/de43791e-7380-49cb-a475-02558ccf3fd1)


 4.Which movie rating (e.g., PG, PG-13, R) has the highest number of titles in the inventory, and how can this information help optimize inventory management?


![Screenshot 2025-01-06 154702](https://github.com/user-attachments/assets/84054e7b-0068-41ad-8c92-3e31e13db886)


 5.What is the total count of PG-rated movies that have been rented, and what does this indicate about customer preferences?


![Screenshot 2025-01-06 154803](https://github.com/user-attachments/assets/9bf6074e-1c7c-40c0-b0d8-3901393a10a6)


 6.What are the inventory IDs and corresponding film titles for movies that are currently rented out, and how can this data help track rental activity? List of films by Film Name, Category, Language


 ![Screenshot 2025-01-06 154818](https://github.com/user-attachments/assets/8a019700-8dfa-4859-b4aa-eb85a1b6b037)


 7.How many rentals have been made for each movie rating category, and what insights can be drawn regarding the popularity of specific ratings?
How many times each movie has been rented out?


![Screenshot 2025-01-06 154831](https://github.com/user-attachments/assets/bf08bd60-841c-4f31-a51b-42ee4f672239)


 8.How many customers are actively renting movies, and what trends can be observed regarding their rental behavior?


![Screenshot 2025-01-06 154841](https://github.com/user-attachments/assets/8fa874b2-61b6-48bf-821d-5d7045b36cf4)
 

9.What is the number of movies rented for each rental duration category, and how can this data inform inventory optimization?


![Screenshot 2025-01-06 154841](https://github.com/user-attachments/assets/f43b2fc8-e2e9-49a0-9cfb-6820a2ef8fc7)


 10.Which movie titles are rented most frequently, and how can this information help identify popular trends?


![Screenshot 2025-01-06 154841](https://github.com/user-attachments/assets/af8071f2-26f5-4ddd-b69b-f11d67d91096)


 11.Who are the top customers based on the number of movies rented, and how can this data be used for personalized marketing strategies?


![Screenshot 2025-01-06 154841](https://github.com/user-attachments/assets/3a407862-b09c-4eca-bfd0-dc6be329739c)


12.What is the total revenue generated by each customer, and how can this information highlight valuable customers for loyalty programs?


![Screenshot 2025-01-06 154841](https://github.com/user-attachments/assets/e10d365b-0aad-47f8-bd3d-8fdd200e03ac)


Most Spending Customer so that we can send him/her rewards or debate points

-- Which Store has historically brought the most revenue?

-- How many rentals we have for each month

-- Reward users who have rented at least 30 times (with details of customers)

-- Could you pull all payments from our first 100 customers (based on customer ID)

-- Now I’d love to see just payments over $5 for those same customers, since January 1, 2006

-- Now, could you please write a query to pull all payments from those specific customers, along -- with payments over $5, from any customer?

-- We need to understand the special features in our films. Could you pull a list of films which -- include a Behind the Scenes special feature?

-- unique movie ratings and number of movies

-- Could you please pull a count of titles sliced by rental duration?

-- RATING, COUNT_MOVIES,LENGTH OF MOVIES AND COMPARE WITH RENTAL DURATION

-- I’m wondering if we charge more for a rental when the replacement cost is higher. -- Can you help me pull a count of films, along with the average, min, and max rental rate, -- grouped by replacement cost?

-- “I’d like to talk to customers that have not rented much from us to understand if there is something -- we could be doing better. Could you pull a list of customer_ids with less than 15 rentals all-time?”

-- “I’d like to see if our longest films also tend to be our most expensive rentals. -- Could you pull me a list of all film titles along with their lengths and rental rates, and sort them -- from longest to shortest?”

-- CATEGORIZE MOVIES AS PER LENGTH

-- CATEGORIZING MOVIES TO RECOMMEND VARIOUS AGE GROUPS AND DEMOGRAPHIC

-- “I’d like to know which store each customer goes to, and whether or -- not they are active. Could you pull a list of first and last names of all customers, and -- label them as either ‘store 1 active’, ‘store 1 inactive’, ‘store 2 active’, or ‘store 2 inactive’?”

-- “Can you pull for me a list of each film we have in inventory? -- I would like to see the film’s title, description, and the store_id value -- associated with each item, and its inventory_id. Thanks!”

-- Actor first_name, last_name and number of movies

-- “One of our investors is interested in the films we carry and how many actors are listed for each -- film title. Can you pull a list of all titles, and figure out how many actors are -- associated with each title?”

-- “Customers often ask which films their favorite actors appear in. It would be great to have a list of -- all actors, with each title that they appear in. Could you please pull that for me?”

-- “The Manager from Store 2 is working on expanding our film collection there. -- Could you pull a list of distinct titles and their descriptions, currently available in inventory at store 2?”

-- “We will be hosting a meeting with all of our staff and advisors soon. Could you pull one list of all staff -- and advisor names, and include a column noting whether they are a staff member or advisor? Thanks!”
