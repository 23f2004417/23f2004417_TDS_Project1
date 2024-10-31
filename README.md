**Scraping the Data:**

I reviewed the GitHub REST API documentation to understand about the search endpoints. 
Using Python's requests library, I scraped user and repository data by using the API. 
Then the Company names were cleaned as necessary, and boolean fields were converted into lowercase strings as specified.

**Surprising Facts:**

I found three users who do not have any public repositories but still have a countable number of followers. 
Additionally, hireable users tend to follow more people than those who are not hireable.

**Actions for Developers:**

Increasing the number of repositories and the length of your bio can help in increasing the number of followers as there is a positive correlation between number of repositories or length of bio against the number of followers.

You can find all the code I used to scrape, analyze, and answer these questions in the following Google Colab notebook link: 
(https://colab.research.google.com/drive/1465n2I1x_Jtd56KuWcK8Yn7eHksQeKjS?usp=sharing).

**File for the same have also been uploaded. (TDS_Project_1.ipynb)**
