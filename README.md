#  <img src=https://user-images.githubusercontent.com/55955478/235878802-1c423764-f355-47b0-b926-f9380334defd.png height=48 width=48> LINKEDIN JOBS ANALYSIS
<img src=https://github.com/RaviKumarAgrawal/Linkedin-Jobs-Analysis/assets/128930068/28c73e70-72df-42f7-b4b7-b91718a77109 height=300 width=1200>
<br> 
This repository presents an end-to-end analysis of LinkedIn's professional networking platform's Jobs section. The project aims to extract over 500 job details from LinkedIn's website using the Python library, Selenium, and organize the information into specific formats by creating three tables. Additionally, the project involved data cleaning and exploratory data analysis using Pandas and Numpy libraries. MySQL and MS-Excel were utilized to derive insights from the dataset. Power BI was used to visualize the results. Finally, a web page was created to present relevant job information based on the skills listed in the dataset. The page was hosted on the cloud for wider access.
<br>

## <img src=https://user-images.githubusercontent.com/106439762/181935629-b3c47bd3-77fb-4431-a11c-ff8ba0942b63.gif height=50 width=50 >  User's Manual

|Files | Description |
|-----|--------|
|Comapny.csv|The file contain details of company|
|DASHBOARD_final.xlsx|The file contains of Deshboard|
|Details.csv|The file contains details of employee|
|Jobs.csv|The file contains jobs details|
|Linkedin Job Analysis Script.sql|This script contains insights derived in mysql-workbench|
|Linkedin_Project.ipynb|This is our Data Scrapping file used to scrape linkedin jobs section|
|PPT.pdf|This is final PPT of insights|
<br>

## <img src=https://user-images.githubusercontent.com/106439762/181937125-2a4b22a3-f8a9-4226-bbd3-df972f9dbbc4.gif height=48 width=48> Tools & Technology Used:
![image](https://user-images.githubusercontent.com/55955478/235897588-756e9ed4-33b3-45f6-83c8-4f68988fe8ba.png)


<br>

## <img src=https://user-images.githubusercontent.com/106439762/178428775-03d67679-9aa4-4b08-91e9-6eb6ed8faf66.gif height=48 width=48> Methodology:

  1. Implemented web scraping on the LinkedIn jobs section using the Python library Selenium. Leveraged its capabilities to extract and retrieve the following attributes from the job listings:


| Attribute | Feature's Meaning |
|-----------|-----------|
|`location` | The location of the job |
|`designation`| The designation of the job |
|`name`| Name of the company |
|`industry` | Industry in which the company operates |
|`employees_count`| Count of employees |
|`linkedin_followers` | Number of followers on linkedin |
|`involvement` | the nature of involvement in the job, for instance: Full-time, part-time |
|`level` | The seniority level like Mid-Senior level |
|`total_applicants` | total number of applicants |
		

  2. Utilized Pandas to perform data cleaning and exploratory data analysis (EDA), and seamlessly imported the CSV files into MySQL for comprehensive analysis and further insights extraction.

3. Skillfully employed various SQL clauses such as GROUP BY, ORDER BY, HAVING, and more to manipulate the data, enabling in-depth analysis and extraction of valuable insights.




<br>
  
## <img src=https://user-images.githubusercontent.com/106439762/178803205-47a08ce7-2187-4f96-b301-a2b68690619a.gif height=48 width=48> Results/Insights:
  
<p align="center"><a><img src=https://github.com/RaviKumarAgrawal/Linkedin-Jobs-Analysis/assets/128930068/3bcd8d47-d6d9-4228-b94c-da8046b142ed
 height=400 width=1000></a></p>
<p align="center"><a><img src=https://github.com/RaviKumarAgrawal/Linkedin-Jobs-Analysis/assets/128930068/1cd4907c-9135-41b3-a3e4-aae7d9806534
 height=400 width=1000></a></p>
<p align="center"><a><img src=https://github.com/RaviKumarAgrawal/Linkedin-Jobs-Analysis/assets/128930068/aee67ec7-f1a6-477c-b6e7-23a3d838551a
 height=400 width=1000></a></p>
<p align="center"><a><img src=https://github.com/RaviKumarAgrawal/Linkedin-Jobs-Analysis/assets/128930068/f58d0170-98a6-4d86-b6db-dd13386aa024
 height=400 width=1000></a></p>
 
<br>
  
## <img src=https://cdn1.vectorstock.com/i/1000x1000/45/70/dashboard-icon-vector-22894570.jpg height=50 width=50> :

<img width="912" alt="link_desh" src="https://github.com/RaviKumarAgrawal/Linkedin-Jobs-Analysis/assets/128930068/360de1fd-9570-4dce-8500-b072893594b0">

<br>
  
## <img src=https://user-images.githubusercontent.com/108053296/185756908-fbb62168-d923-48f2-992f-b8e2fde848fe.gif height=50 width=50> Conclusions:
  
  1. Most jobs are being posted by small-size Companies but applicants are apprently applying in Large-size Companies.
  2. Most applicants are applying in Chennai based companies, but more jobs are there in Mumbai and Bangalore based companies
  3. Significantly higher number of applicants in large and small size companies as compared to medium size companies
  4. Top three states with maximum job openings are Tamil Nadu, Karnataka and Maharastra.
  5. Digital marketing has the most opportunities
  6. About half of the total openings are in IT industry
  7. AI is most required skills.
<br>
