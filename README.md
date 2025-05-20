# Instruction：
Original data :test.csv

Run the notebooks sequentially

Task 1: Sentiment Labelling.Uses cardiffnlp/twitter-roberta-base-sentiment from Hugging Face to label each email.
  Output: sentiment_practice_output.csv with sentiment scores.

Task 2: Explore sentiment trends.
  
Task 3: Calculate sentiment scores per employee.  
  Output：monthly_employee_scores.csv
  
Task 4: Rank employees based on sentiment.

  Output:top_negative_employees.csv;top_positive_employees.csv
  
Task 5: Detect flight risks using rolling analysis.

Task 6: linear regression to predict future sentiment trends.

# Overview：
Top 3 most positive employee(from all the data):
1	johnny.palmer@enron.com
2	eric.bass@enron.com
3	lydia.delgado@enron.com

Top 3 most negative employee(from all the data):
1	rhonda.denton@enron.com
2	don.baughman@enron.com
3	kayne.coulter@enron.com

monthly top 3 most positive and negative can be found in top_negative_employees.csv;top_positive_employees.csv

Top 4 Employees at Highest Risk of Leaving(Based on sending 4 or more negative emails within any rolling 30-day window)
1.bobette.riner@ipgdirect.com
2.don.baughman@enron.com
3.john.arnold@enron.com
4.sally.beck@enron.com

Top 3 Most Active Employees(Based on total message count)
1.lydia.delgado@enron.com
2.john.arnold@enron.com
3.patti.thompson@enron.com

These individuals sent the highest number of emails overall, indicating high engagement or visibility in internal communication.

john.arnold@enron.com appears on both lists, meaning he is highly active but also flagged as a flight risk due to his negative sentiment patterns.
