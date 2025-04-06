# Home_Sales

In this activity, we were asked to use PySpark from Apache to analyze some Home Sale Data provided to us by AWS S3.

First, we had to load up the dependencies and create an instance for PySpark.  

Then we fired up SQL for PySpark.

Following that we created a temporary view and the did some SQL queries to answer questions asked in the module.  

We timed the repsonse of the queries three times.  One stragith up, one using a cached table and one using a partition.

For my computer, the one that ran the fastest was actually the cached query.  It beat the partition by .04 when both queries were ran twice.

We than uncached the table and ended the module challenge.


--- Just a note for the graders, thank you so much for all of your feedback throughout the course.  I appreciate the time and thought from each and everyone one of you.

All the best in the future,

Chris
