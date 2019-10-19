# Log-analysis
Log-analysis is internal reporting tool that will use information from the database to discover what are the most populer articles on the site, whos are the most populer authors and when was more than 1% of requests lead to errors in the site.

# How to run?
To run the program you need first to load the database which called "news" from the file "newsdata.sql" after locate it into the vagrant directory, which is shared with your virtual machine. Then you need to load the file Log-analysis.py.

## Examples:
### Command Line:
`psql -d news -f newsdata.sql`

`python Log-analysis.py`

# License 
Log-analysis is created by Hesham Ghatasheh-Udacity Nanodegree student.