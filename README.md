# Amazon_Vine_Analysis
 
<b>Overview</b><br>
The purpose of this project was to analyze data provided by Amazon on paid product reviews as part of the Amazon Vine program. This program provides customer reviews for products and companies, in return for payment or incentives. By connecting RDS and PostgresSQL to Google Colab, we are able to create a database for the data and organize it to better understand the results.

<b>Results</b><br>

<i>How many Vine reviews and non-Vine reviews were there?</i><br>

According to the data, there are 94 Vine program reviews and 40471 non-Vine program reviews.

<img width="170" alt="Screen Shot 2022-06-21 at 2 54 12 PM" src="https://user-images.githubusercontent.com/100445222/174876659-1be78a2b-205f-4299-83bf-6314124e4ebb.png">

<i>How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?</i><br>

Of the 94 Vine program reviews, a total of 48 were 5 star.  Only 15,663 of the 40,471 non-Vine reviews were 5 star.
<img width="285" alt="Screen Shot 2022-06-21 at 2 54 16 PM" src="https://user-images.githubusercontent.com/100445222/174876680-12836c4b-4735-431d-af60-1e580784ae21.png">

<i>What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?</i><br>

Over half of the total Vine reviews were 5 star, with a total of 51.06%.  Only 38.70% of the non-Vine reviews were 5 star.
<img width="485" alt="Screen Shot 2022-06-21 at 2 54 19 PM" src="https://user-images.githubusercontent.com/100445222/174876688-f28a86bf-3a08-4b71-8236-07cd2b15136d.png">

<b>Summary</b><br>

Based on the analysis, there is positivity bias in the paid Vine review program.  Reviews that were paid for in this project were more positive than the reviews provided by customers who had no incentives. Another analysis to further prove a bias could include an incentive measure based on how much a customer receives were reviewing.  Higher incentives could mean a customer is more likely to provide 5 star, higher quality reviews.
