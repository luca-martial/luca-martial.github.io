---
layout: single
permalink: /projects/
# title: "Data Science Projects"
author_profile: true
---

<!-- link for all embedded things: https://mmistakes.github.io/minimal-mistakes/docs/helpers/ -->

# Featured Projects
------

### Montreal Temperature Spiral (1872-2019)
*December 2019 | Languages: Python*

The goal of this project was to create an animated spiral of Montreal's variation in temperature from 1872 to 2019.

**Background:** [Ed Hawkins](http://www.met.reading.ac.uk/~ed/home/index.php), a climate scientist, unveiled [an animated visualization](http://www.climate-lab-book.ac.uk/spirals/) in 2017 which captivated the world. This visualization showed the deviations of the global average temperature from 1850 to 2017. It was reshared millions of times over Twitter and Facebook and a version of it was even shown at the opening ceremony for the Rio Olympics.

This animation was created with the help of [an article on Dataquest.io](https://www.dataquest.io/blog/climate-temperature-spirals-python/) written by Srini Kadamati.

Historical weather data was retrieved from [Environment Canada's website](https://climate.weather.gc.ca/). Recordings from the Montreal McGill Station (Dr. Penfield Street/Redpath Street) provided monthly weather data from 1872 to 1993 while recordings from the Montreal McTavish Station (McTavish Street/Dr. Penfield Street), just 700 meters away, provided daily weather data from 1994 to 2019. Combining data from both sources may constitute a source of error, but with the unavailability of continuous weather recordings from 1872 to 2019 from a single station, there appears to be no alternative solution.

Code can be viewed on [GitHub](https://github.com/luca-martial/Montreal-Temperature-Spiral).

{% include video id="1ZxbsKE51XfYHBWvNHgN0LkLx2rM5-Waa" provider="google-drive" %}

<!-- https://drive.google.com/open?id=1ZxbsKE51XfYHBWvNHgN0LkLx2rM5-Waa -->

# All Projects
------
This is a list of all completed projects.

### Analyzing a Star Wars Survey
*July 2019 | Languages: Python*
{% include figure image_path="/images/starwars.png" caption="**While waiting for Star Wars: The Force Awakens to come out, the team at [FiveThirtyEight](https://fivethirtyeight.com/) became interested in answering some questions about Star Wars fans. In particular, they wondered: does the rest of America realize that “The Empire Strikes Back” is clearly the best of the bunch?**

**The team needed to collect data addressing this question. To do this, they surveyed Star Wars fans using SurveyMonkey. They received 835 total responses, which are downloadable from their [GitHub repo](https://github.com/fivethirtyeight/data/tree/master/star-wars-survey).**

**The goal of this project was to conduct a rapid cleaning, exploration and analysis of the data.**

**Code can be viewed on [GitHub](https://github.com/luca-martial/Star-Wars-Survey).**"%}


### Analyzing NYC High School Data
*June 2019 | Languages: Python*
{% include figure image_path="/images/sat.png" caption="**New York City has published the following data on student [SAT](https://en.wikipedia.org/wiki/SAT) scores by high school, along with additional demographic data sets:**

- **SAT scores by school - SAT scores for each high school in New York City**
- **School attendance - Attendance information for each school in New York City**
- **Class size - Information on class size for each school**
- **AP test results - Advanced Placement (AP) exam results for each high school (passing an optional AP exam in a particular subject can earn a student college credit in that subject)**
- **Graduation outcomes - The percentage of students who graduated, and other outcome information**
- **Demographics - Demographic information for each school**
- **School survey - Surveys of parents, teachers, and students at each school**

**New York City has a significant immigrant population and is very diverse, so comparing demographic factors such as race, income and gender with SAT scores can be an interesting way to explore whether the SAT is a fair test. This was the goal of this quick analysis.**

**Code can be viewed on [GitHub](https://github.com/luca-martial/Analyzing-NYC-High-School-Data).**"%}


### Analyzing Employee Exit Surveys
*June 2019 | Languages: Python*
{% include figure image_path="/images/employee.png" caption="**In this project, I worked with exit surveys from employees of the [Department of Education, Training and Employment](https://en.wikipedia.org/wiki/Department_of_Education_and_Training_(Queensland)) (DETE) and the Technical and Further Education (TAFE) institute in Queensland, Australia.**

**I played the role of a data analyst and pretended my stakeholders want to know the following:**

- **Are employees who only worked for the institutes for a short period of time resigning due to some kind of dissatisfaction? What about employees who have been there longer?**
- **Did more employees in the DETE or TAFE institute end their employment because they were dissatisfied in some way?**
- **How many people in each age group resgined due to some kind of dissatisfaction? Are younger employees resigning due to some kind of dissatisfaction? What about older employees?**

**I had to combine the results for *both* surveys to answer these questions. However, although both used the same survey template, one of them customized some of the answers. I therefore aimed to perform lots of data cleaning before getting started analyzing.**

**Code can be viewed on [GitHub](https://github.com/luca-martial/Analyzing-Employee-Exit-Surveys).**"%}


### Job Outcomes of College Students Between 2010 and 2012 in the U.S.
*May 2019 | Languages: Python*
{% include figure image_path="/images/college.png" caption="**In this project, I worked with a dataset on the job outcomes of students who graduated from college between 2010 and 2012. The original data on job outcomes was released by [American Community Survey](https://www.census.gov/programs-surveys/acs/), which conducts surveys and aggregates the data. [FiveThirtyEight](https://fivethirtyeight.com/) cleaned the dataset and released it on their [Github repo](https://github.com/fivethirtyeight/data/tree/master/college-majors).**

**This project was done to showcase how using the pandas plotting functionality along with the Jupyter notebook interface allows us to explore data quickly using visualizations.**

**Using visualizations, I explored the following questions from the dataset:**

- **Do students in more popular majors make more money?**
- **How many majors are predominantly male? Predominantly female?**
- **Which category of majors have the most students?**

**Code can be viewed on [GitHub](https://github.com/luca-martial/Earnings-Based-on-College-Majors).**"%}


### Exploring Hacker News Posts
*April 2019 | Languages: Python*
{% include figure image_path="/images/hacker-news.png" caption="**In this project, I worked with a data set of submissions to popular technology site [Hacker News](https://news.ycombinator.com/).**

**Hacker news is a site started by the startup incubator [Y Combinator](https://www.ycombinator.com/), where user-submitted stories (known as 'posts') are voted and commented upon, similar to reddit.**

**I was specifically interested in posts whose titles begin with either 'Ask HN' or 'Show HN'. Users submit 'Ask HN' posts to ask the Hacker News community a specific question. Likewise, users submit 'Show HN' posts to show the Hacker News community a project, product, or just generally something interesting.**

**I compared these two types of posts to determine the following:**

- **Do Ask HN or Show HN posts receive more comments on average?**
- **Do posts created at a certain time receive more comments on average?**
- **Do Ask HN or Show HN posts receive more points on average?**
- **Do posts created at a certain time receive more points on average?**

**Code can be viewed on [GitHub](https://github.com/luca-martial/Hacker-News-Posts-Analysis).**"%}


### Ebay Car Sales Analysis
*March 2019 | Languages: Python*
{% include figure image_path="/images/ebay_car.png" caption="**In this project, I worked with a dataset of used cars from eBay Kleinanzeigen, a [classifieds](https://en.wikipedia.org/wiki/Classified_advertising) section of the German eBay website.**

**The dataset was originally [scraped](https://en.wikipedia.org/wiki/Web_scraping) and uploaded to [Kaggle](https://www.kaggle.com/orgesleka/used-cars-database/data). A few modifications were made by [Dataquest](https://www.dataquest.io/) to the original dataset that was uploaded to Kaggle:**

- **The dataset was trimmed down to 50,000 data points from the full dataset**
- **The dataset was dirtied a bit to more closely resemble what could be expected from a scraped dataset (the version uploaded to Kaggle was cleaned to be easier to work with)**

**This was done to allow data scientists to put into use their data cleaning skills.**

**The aim of this project was to clean the data and analyze the included used car listings.**

**Code can be viewed on [GitHub](https://github.com/luca-martial/Exploring-Ebay-Car-Sales-Data).**" %}


### Profitable App Profiles for the App Store and Google Play Markets
*February 2019 | Languages: Python*
{% include figure image_path="/images/app.png" caption="**Context: A company builds Android and iOS mobile apps that are free to download and install. Their main source of revenue consists of in-app ads. This means that the more users they get, the more people will be seeing the ads, the more revenue they will be able to generate.**

**Goal: My goal was to help the company's developers understand what different kinds of apps are likely to attract more users on Google Play and the App Store.**

**Code can be viewed on [GitHub](https://github.com/luca-martial/Popular-Apps-Project).**"%}