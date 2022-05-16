# Web Scraping Linkedin Job Page with Selenium Python

<img src="https://cdn-images-1.medium.com/max/912/1*dP-N_337XhsvE4VpgwkTQA.jpeg" width="450" height="400">

>Selenium is a free (open-source) automated testing framework used to validate web applications across different browsers and platforms.

### You can read more detailed explanation of this project in my Medium blog

https://medium.com/@kurumert/web-scraping-linkedin-job-page-with-selenium-python-e0b6183a5954

## What's Inside?
---
In this project, I have used Selenium library to automate the scraping process, navigate between pages, fill out forms (such as login credentials), click links, etc. Briefly, besides the data scraping part, Selenium was used to automate the following steps mentioned below to manage some actions until we access the pages where we will scrape the data. I have scraped the job offers and scraped their information by visiting 14 pages with each page having 25 job offers.

>Automated Steps
1. Enter to Linkedin login page
2. Spot the cookies pop-up and click Accept cookies
3. Fill E-Mail Address and Password areas and click Login 
4. Click on the Jobs  from the section above 
5. Search for job positions Junior Data Analyst in Spain
6. Scroll down till the end of the page while collecting the link of each displayed Job offer
7. Go to the next page when it is the end of the page while keep collecting links 
8. After all links are collected, go to the each link
9. Click the "See More" button the expand the job description text.
10. Scrape the desired data 

---

>Items Scraped:
1. Job Title
2. Company Name
3. Company Location
4. Job Description
5. Work Method (Hybrid, Remote, On-Site)
6. Experience Level
7. Post Date



Extra:

You can check my medium post where I have analyzed the data and found some useful insights:
https://medium.com/@kurumert/the-insights-behind-the-data-field-job-offers-on-linkedin-4edb5203525b
