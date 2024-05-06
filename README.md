# Hotel Review Analysis for the Leonardo Group of Hotels

This project analyzes guest reviews from Booking.com to provide insights for the Leonardo Group of Hotels. By examining customer feedback, the project aims to identify areas for improvement and help the hotel chain enhance their operations and increase customer satisfaction.

## Business Problem

Booking.com is a popular online travel agency that facilitates the booking of accommodations, flights, rental cars, and other travel-related services worldwide. Booking.com's hotel review system empowers travelers with authentic insights through user-generated ratings and detailed feedback. Guests rate their experiences on a scale of 1 to 10, accompanied by specific comments, ensuring transparency and credibility.
In this project, reviews are collected from the Leonardo Group of Hotels, which owns over 200 four-star hotels across Europe. The goal is to provide insights to help them enhance their business and reach five-star status.

## Tools and Libraries Used

- `Python:` The analysis is conducted in Python using a Jupyter notebook.
- `Libraries:` BeautifulSoup, requests, pandas, matplotlib, seaborn, wordcloud, and scikit-learn.

## Running the Analysis

To run this analysis, ensure you have Python installed along with the necessary packages mentioned above. Clone this repository and execute the analysis in the provided Jupyter notebook `Hotel_Review_Analysis_Leonardo_Group.ipynb`. 
The dataset will be generated through the scraping function.

## Visualizations

- `Bar Charts:` To display review scores and distribution of positive/negative sentiments.
- `Word Clouds:` For understanding frequently mentioned words in customer reviews.
- `Trend Graphs:` Showing changes in review scores over time.

## Steps and Insights

This project is focused on making things better for Leonardo group of hotels by sorting customer reviews from Booking.com into three groups: staff, quality, and others categories. We have used web scraping to gather these reviews and then developed a function that automatically puts each review into the right category. We then used that dataset of 300 reviews to build and train multiple machine learning models.

Leonardo Hotels, with over 200 locations in Europe, can use this system to see what guests think about their staff, the condition of their hotels, and the extras they offer. By focusing on these specific areas, they can make quick changes that have a big impact.

However, the machine learning models must be continuously monitored and developed by adjusting hyperparameters, incorporating additional features based on latest reviews, and recalibrating the classification algorithms to adapt to changes in customer reviews.
