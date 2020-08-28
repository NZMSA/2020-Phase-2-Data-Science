# Reddit data
The posts csv file contain information about the Reddit posts on Tesla.<br>
<br> 
See link here: https://www.reddit.com/r/teslamotors/ <br>
* Title - Title of the post
* URL - url for the post (each post has its own url where you can see the comments for that post)
* Body - The contents of each post 
* Upvotes - The number of upvotes of the post
* Time - Timestamp of post(I have converted it from utc timestamp for you)
* Key - The is a unique key allocated to each post. This is important because it links the post from the posts file
with the associated comments from the comments file.  
<br>

The comments csv file contains information of comments/replies made to each of the posts in the posts file.<br>
* Reply - The comments made in response to the post
* Time - Timestamp of the comments
* Upvote - Number of upvotes of the comment
* Key - This is a key that associates each comment in the comments file with the post it belongs to in the posts file.<br>
<br>
---
### The PRAW module
Since you are not expected to scrap the Reddit API yourself I won't go into too much detail here. 
But if you are interested, the link below is very beginner friendly and is also how I got started with PRAW.
* https://www.privateproxyreviews.com/scrape-reddit-using-praw-python/#reddit-has-made-scraping-more-difficult-here-s-why
<br>

Once you have a handle on the basics, the PRAW documentation provides an comprehensive overview of PRAW's functionalities
* https://praw.readthedocs.io/en/latest/ <br>
