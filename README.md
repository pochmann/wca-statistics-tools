WCA-forum-statistics-tool
=========================

Produces statistics from WCA data for speedsolving.com forum posts. Automatically updates a local database using the WCA export. Not an official WCA tool.

You write queries in `*.in` files and the tool runs them and produces `*.out` files that contain the results nicely formatted and documented, ready to copy&paste into the forum.

What you need and where to get it (if you don't have it already):
- [Python 3](https://www.python.org/downloads/) (to run the tool)
- [MySQL Community Server](http://dev.mysql.com/downloads/) (to hold the WCA export data)
- A database and user, see the settings section at the start of the tool.
- [MySQL Connector/Python](http://dev.mysql.com/downloads/connector/python/) (so Python can access the database)
