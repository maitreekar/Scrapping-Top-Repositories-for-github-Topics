# Scrapping-Top-Repositories-for-github-Topics
Used Python and its ecosystem of libraries to scrape information from a website.

 Web scraping is the process of extracting and parsing data from websites in an automated fashion using a computer program. It’s a useful technique for creating datasets for research and learning. 

 
# Here are the steps we'll follow:

We're going to scrape https://github.com/topics
We'll get a list of topics. For each topic, we'll get topic title, topic page URL and topic description
For each topic, we'll get the top 25 repositories in the topic from the topic page
For each repository, we'll grab the repo name, username, stars and repo URL
For each topic we'll create a Dataframe in the containing the user_name, repository name, its url and number of ratings

# Libraries of python Used:
Pandas
Request
BeautifulSoup


