# Interview

Full Stack Developer Assessment Question:
 
1) Use GitHub job API to extract all job posts and insert into db.
  
- GitHub job API URL ref :- https://jobs.github.com/api
 
2) Create a database (SQLite or any other in-memory database) and store the results.
Expected URL Samples:
- sync_jobs(to fetch job details and store it in db)  :-  /jobs/sync/       [POST]
- list jobs   :-   /jobs/        [GET]
- list jobs with filter   :-   /jobs?location=&quot;xyz&quot;, /jobs?title=&quot;abc&quot;    [GET]
 
3) Create a single page application to display the company and job details.
