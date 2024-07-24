# Wrangling and Analyzing WeRateDogs Tweets

This project involves wrangling and analyzing the tweet archive of the Twitter user @dog_rates, also known as WeRateDogs. The process included the following main steps: gathering, assessing, cleaning, storing, analyzing, and visualizing the data.

## Gathering
Data from three sources were gathered as follows:

1. **twitter-archive-enhanced**: A CSV document containing the archive was loaded into the Jupyter notebook.
2. **image-predictions**: A TSV document was downloaded into a predictions folder using the requests library and then loaded into the notebook.
3. **tweet-json**: A JSON file containing additional data was read. Counts of retweets and favorites were extracted for each tweet ID in the file and read into a DataFrame.

## Assessing
The gathered datasets were assessed visually and programmatically for issues. These issues were then categorized into quality issues and tidiness issues.

## Cleaning
The three tables were merged into one table. Each identified issue was addressed by:
1. Defining the solution.
2. Running the code to fix the issue.
3. Testing to confirm the resolution.

Tidiness issues were addressed first, followed by quality issues.

## Storing
The cleaned data was exported to a CSV file named `twitter_archive_master.csv`.

## Analyzing and Visualizing
An analysis was performed on the cleaned data. Insights were generated, accompanied by visualizations.

## Acknowledgment
This project was completed as part of the requirements for the Udacity Data Analyst Nanodegree.

## License
This project is licensed under the terms of the MIT license.
