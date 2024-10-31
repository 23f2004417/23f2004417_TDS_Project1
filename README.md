**Scraping the Data:**

* I reviewed the GitHub REST API documentation to understand about the search endpoints. 
Using Python's requests library, I scraped user and repository data by using the API. 
Then the Company names were cleaned as necessary, and boolean fields were converted into lowercase strings as specified.

**Surprising Facts:**

* I found three users who do not have any public repositories but still have a countable number of followers. Hireable users tend to follow more people than those who are not hireable. Additionally, Hireable users are 6.6% more likely to share their email addresses than non-hireable users.

**Actions for Developers:**

* Increasing the number of repositories or the length of your bio, in terms of word count, can help increase the number of followers, as there is a positive correlation between the number of repositories or bio length and the number of followers.

You can find all the code I used to scrape, analyze, and answer these questions in the following Google Colab notebook link: 
(https://colab.research.google.com/drive/1465n2I1x_Jtd56KuWcK8Yn7eHksQeKjS?usp=sharing).

**File for the same have also been uploaded. (TDS_Project_1.ipynb)**
Please use your GitHub Personal Access Token to be able to Scrape the Data using the above file/link for (Basel:10) and Analyse it.
