# My Project Portfolio

#### Technical Skills: SQL, Python, Excel, Tableau

## Personal Background
Hi, My name is Will and I am looking to grow my skills working with data to solve analytical problems. I am a recent computer science graduate with course experience in Data Science, Web Development, and Information Retrieval. These classes have given me an understanding of how to identify problems that can be addressed with analytical solutions, gather and manipulate data sources, and apply analysis to achieve insights. In my free time, I am interested in using data analytics to answer complex business and sports questions.

## Projects

### NBA Organization Efficiency - (Python, SQL, Tableau)
While looking at different NBA statistics, I wanted to know which organizations managed their resources well when it came to player spending and coaching. I first gathered data that tracked player efficiency, coaching efficiency, and player salaries on NBA teams for the past 19 seasons. After cleaning the data using Python, I wrote queries to insert the files into Microsoft SQL Server where I created 3 statistics that represented the efficiency of each NBA team.

Coaching Efficency Difference:
- Measures the difference between the average win share produced by players under a specific coach compared to the rest of their career. I then used the average of this metric for each NBA team.

Wins per $1 Million:
- Measures the ratio of win shares to total salary for a players career with a team. I used the average of this metric for each player in an organization.

Dollars Spent per Regular Season Win:
- Finds the average ratio of regular season wins to player salary for each NBA team.

These statistics can be viewed on a Tableau dashboard[here](https://public.tableau.com/app/profile/william.czech/viz/nba_team_analytics_proj/Dashboard2).

[Link to code/repository](https://github.com/wczech23/nba_data_project)

### Job Description Keyword Analyzer - (Python)
While applying for jobs, I was interested in how I could improve my performance with the applicant tracking systems (ATS) that analyzed my resume. To improve the scoring my resume earned from this system, I wanted to create an app that gathered 100s of job applications for any job title and analyzed the relevance of words within the job descriptions to understand which words were most valuable to include in my resume. I first web scraped 1000s of Wikipedia pages to gather enough text to build a word frequency model. After applying Python natural language processing libraries to create this model, I used the Adzuna job application API to gather job descriptions based on the search for a specific job title. Using the model and description data, I was able to find the most relevant keywords to add to my resume to make my applications more appealing to the applicant tracking system.

[Link to code/repository](https://github.com/wczech23/keywordanalyzer)
