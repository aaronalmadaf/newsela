# Newsela Challenge Answers
Please note that this assesment was solved using Python and Jupyter Notebook as I was told any language was accepted (language agnostic). 
Below I pasted the solutions, however, I strongly recommend reviewing the Jupyter File directly as it has more analytics and info. 

Please note that this assessment was solved using Python and Jupyter Notebook, as I was told any language was accepted (language agnostic).
Below I pasted the solutions; however, I strongly recommend reviewing the Jupyter file directly as it has more analytics and information.

<h3>Statements</h3> Take a look at this public BigQuery dataset of Stack Overflow posts. <br> Please provide queries that answer the following prompts: <br> 1. What tags on a Stack Overflow question lead to the most answers and the highest rate of approved answers for the current year? What tags lead to the least? How about combinations of tags? <br> 2. For posts that are tagged with only ‘python’ or ‘dbt’, what is the year-over-year change of question-to-answer ratio for the last 10 years? How about the rate of approved answers on questions for the same time period? How do posts tagged with only ‘python’ compare to posts only tagged with ‘dbt’? <br> 3. Other than tags, what qualities on a post correlate with the highest rate of answers and approved answers? Feel free to get creative. 

<h3>Problem Solving</h3> <h4>1-a. What tags on a Stack Overflow question lead to the most answers and the highest rate of approved answers for the current year?</h4> 
A pandas DataFrame was obtained with the tags with more answers and more accepted answers. (Please refer to the Jupyter file to see the DataFrame.) 

<h4>1-b. What tags lead to the least?</h4> 
A pandas DataFrame was obtained with the tags with fewer answers and fewer accepted answers. (Please refer to the Jupyter file to see the DataFrame.) 

<h4>1-c. How about combinations of tags?</h4> 
A pandas DataFrame was obtained with the combinations of tags with more answers and more accepted answers. (Please refer to the Jupyter file to see the DataFrame.) 

<h4>2-a. For posts that are tagged with only ‘python’ or ‘dbt’, what is the year-over-year change of question-to-answer ratio for the last 10 years?</h4> 
Overall, the trend is negative. There are more questions, but the number of answers remained the same. A pandas DataFrame was obtained showing the yearly trends. (Please refer to the Jupyter file to see the DataFrame.) 

<h4>2-b. How about the rate of approved answers on questions for the same time period?</h4> 
Overall, the trend is negative. There are more questions, but the number of accepted answers remained the same. A pandas DataFrame was obtained showing the yearly trends. (Please refer to the Jupyter file to see the DataFrame.) 

<h4>2-c. How do posts tagged with only ‘python’ compare to posts only tagged with ‘dbt’?</h4> 
For Python, the number of questions increased from 2012 to 2020; then it decreased. However, the number of answers had low variance from 2013 to 2021.<br> Regarding the ratio of questions to answers, the ratio was 2.4 in 2012 and has been decreasing since then. Every year the ratio has decreased or stayed the same. <br> Regarding the questions to approved answers, the difference between years is minimal, but with a negative trend. <br> There are more questions but basically the same number of answers. <br> <br> dbt is much newer, and there are records only for three years. Both the number of questions and answers have increased, but it is less popular than Python by a factor of 100–150. <br> Regarding the ratio of questions to answers, it has been stable with negative differences. <br> Regarding the questions to approved answers, the difference between years is minimal, but with a negative trend. <br> <br> Overall, we can assert that based on the number of answers and accepted answers metrics, engagement hasn't gone up with either of the tags; on the contrary, it has decreased. <br> This could be related to the tags/tools/languages, or it could be an overall indicator of platform usage. <br> - Please note that 2022 does not have complete data. 

<h4>3. Other than tags, what qualities on a post correlate with the highest rate of answers and approved answers? Feel free to get creative.</h4> 
The score range and the view counts are positively correlated with the mean number of answers. It is not a perfect correlation, but there is a visible trend. This means that posts that have more views or a higher score tend to have a higher number of answers. <br> The year has a negative correlation, meaning that the most recent years have fewer answers on average. <br> The month of the year and hour of the day have no correlation or trend with the number of answers. The favorite count is uncertain/unclear.

The accepted answer rate is highly correlated with the average number of answers. The more answers there are, the more common it is to have an accepted one.























