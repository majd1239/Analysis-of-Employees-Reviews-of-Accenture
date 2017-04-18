# Analysis of Employees Reviews Accenture Project

<b> Click on the link below to see the rendered visuals of the plots/graphs </b>

http://htmlpreview.github.io/?https://github.com/majd1239/Analysis-of-Employees-Reviews-of-Accenture/blob/master/Accenture_Reviews_Analysis.html


This was my project in preparation for Accenture AcnTechBuild talent recruitment event. We were told to prepare
a pre-built piece of software to present at the event and then participate in an analytics build session. <b>This project
led to a summer internship offer from Accenture.</b>

I wrote the project from scratch. I wanted to present a code that has value in it. I chose to do a data analysis
and visualization using Python. My first step was to search for a relevant data to work on. The company's reviews
by its employees on GlassDoor data was the perfect choice. It provides value to myself and the company.<br>
I will have a good picture of the work atmosphere at Accenture and it will provide the company a good feedback on 
what its employees are thinking.<br>

I encountered an obstacle in getting the data. In turns out that GlassDoor API does not provide a way to extract<br>
the reviews of a company. So I build a script using Selenium framework that web crawl GlassDoor and scraps all the<br>
reviews one by one and write then to a csv file. The actual script can be viewed in the GlassDoor-Reviews-Scrapper repository.<br>
After collecting the reviews and parsing them into proper headers in a csv file, I used Pandas to create a dataframe<br>
to clean the data further. <br>
I cleaned the data and categorized the reviews by five major job fields: Interns, Technology, Consultants, Managers, Analytics and Other.<br>
The following visuals where then created:<br>
- A pie chart visualizing the total reviews number segmented by the five job fields.
- A bar chart was created to visualize the average rating per year of former vs current employees.<br>
- A plot line showing a time series of the incline/decline average rating per job field over the years.<br>
- A sentimental analysis was done on the reviews. They were sorted by the most common word used. A bar<br>
  char visualize the top N Pros or Cons topics. The number of topic is dynamic and can be adjusted.<br>
- A scatter plot was created to visulize the actual content of the reviews sorted by the topics along a <br>
  timeline x-axis and an average rating y-axis. The scatter can be filtered according to the desired selected<br>
  topics and when hovered, it will display the Review content plus that employee advice to the management.<br>

