🎬 Greencycles - Movie Rental Database 📊
Welcome to Greencycles, a movie rental database project! 🎥 This project demonstrates the use of advanced SQL techniques for data analysis, specifically using window functions, aggregation, and ranking in the context of a movie rental system. 🍿

🔍 Project Overview
This repository showcases SQL queries that analyze and manipulate movie rental data. Whether you're calculating running totals, ranking films, or analyzing customer spending patterns, these queries help you better understand how to handle large datasets. 📈

🧠 Key Concepts
This project covers several important concepts, including:

Window Functions 🪟: Perform calculations across a subset of data without changing the level of detail.
Running Totals ➡️: Calculate cumulative values over time, often used in financial reports or time-series analysis.
Aggregations 🔢: Summing, averaging, and counting data across groups or partitions.
Ranking Functions 🏅: Rank items based on specific criteria, such as the highest-grossing movies or the most frequent customers.
Lead and Lag ⏩⏪: Compare values between adjacent rows to calculate changes over time or calculate differences between periods.
📊 SQL Queries Used
Some of the core queries in this project include:

SUM() OVER(PARTITION BY) 💸: Calculate totals or averages for specific groups of data.
RANK() / DENSE_RANK() 🏆: Rank items based on a certain order (e.g., highest to lowest).
LEAD() and LAG() ⏪⏩: Access values from previous or next rows to compare data over time.
FIRST_VALUE() 🔥: Retrieve the first value from a partition, helpful for comparing top performers.
COUNT() OVER(PARTITION BY) 🧮: Count the occurrences of items in specific groups.
📅 How It Works
The SQL queries in this repository focus on analyzing the payment and sales data from the Greencycles movie rental system. From calculating the total spent by customers to analyzing the most rented films, these queries help uncover valuable insights from the database. 💳

Some examples of analysis include:
Customer spending 💰: Analyzing the total amount spent by each customer.
Daily sales 📅: Calculating the running total of sales over time.
Top-ranked films 🎥: Ranking movies based on attributes like length or cost.
Customer rankings 🏅: Finding the top customers based on transaction volume.
⚡ Features
Advanced SQL techniques: Master window functions like OVER(), PARTITION BY, RANK(), LEAD(), and more.
Real-world use cases 🌍: The queries are designed to simulate a real-world scenario, providing insights from movie rental data.
Data analysis focus 🔍: Perfect for those looking to learn or improve their data analysis skills using SQL.
💡 Why This Project?
This project is perfect for those looking to:

🚀 Boost their SQL skills: Learn advanced concepts like window functions, ranking, and aggregations.
🎯 Work with real-world data: Get hands-on experience with a real-world type of data set (movie rentals).
📚 Improve problem-solving: Master how to analyze large data sets and extract meaningful insights using SQL.
🧑‍💻 Getting Started
To get started, simply clone the repository and explore the SQL queries. You can run them on any SQL database that supports window functions (like MySQL, PostgreSQL, or SQL Server). 🖥️

💬 Contributing
If you'd like to contribute to this project, feel free to submit issues or pull requests. 🤝 Whether it’s improving query efficiency, adding more analyses, or fixing bugs — all contributions are welcome!

📃 License
This project is licensed under the MIT License - see the LICENSE file for details. 📜
