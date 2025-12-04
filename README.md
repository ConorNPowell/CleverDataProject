# CleverDataProject
A project for Conor Powell's application for Clever's Data Analyst position.


Hello Welcome to my Project,
In here you will find the raw data, generated reports, and the script I made along with them. 


## Raw Data
This just holds the Google Sheets file split into seperate CSV.


## Full Reports
### write_up.ipynb
This contains my report of all the questions. I ended up writing in Markdown using Jupyter Notebooks as I was already using it for my script


### top_markets.csv
This is the output of my research from my python scripts for top markets which adds onto the markets file. This includes the following new variables of which are talked about more in depth in the write up:
price_change_rate: listing_price_increase_amounts/listing_price_decrease_amounts
listing_closing_rate: listing_closed_count/listings_on_market_count
price_change_per_day: (price_closed_median - price_new_price_list_median)/days_on_market_median


### top_agent.csv
This is the output of my research from my python scripts for top agents which ddes onto the agents file. This includes a few new variables of which are described in more detail in the write up:
median_amount_closed: Retrieved from Sales and Customer data
median_customer_calls: Median calls per closed customer
weight_review_avg: Weighted review average for agent reviews
total_customer_closure_rate: (buyer_closes_2024 + seller_closes_2024)/(buyer_customers_sent_2024 + seller_customers_sent_2024)


## Python Work
### techincal_work.ipynb
My Jupyter Notebook containing all that fun work.

## Thanks for stopping by and taking the time to review my work :)
