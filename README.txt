The following program is meant as an exercise into GUI creation
and database/internet access in a practical setting using
Python 3.4.2.

Introduction --
The following application is meant to directly interact with
Reddit. It is meant for users to be able to post, comment,
vote, etc. on posts and provide a more comprehensive sorting
system.

Operation Goals --
- Allow user to post, comment, and vote on posts
- Color-code posts based on subreddit
- Sort multiple subreddits by option (hot, new, controversial,
	gilded
- Sort subreddit posts based on user priority (1-5 scale)
- Automatic update of posts to subreddits
- Operate in background with little overhead
- Minimalistic GUI
- Fast and lightweight

The program will be crafted entirely in Python. Dependencies:
PRAW, PyQt