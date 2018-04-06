# Facebook Page Post Scraper

## Current to-do:

- Scrape from Feb 1 to Feb 28
- Buzzfeed, ABC News, CBS News, CNN, NBC News, The New York Times, Time, USA Today, The Wall Street Journal

## In-Progress
- Comments: Time (33389), BuzzFeed (30783)

## Completed
- Statuses: The New York Times, Time, USA Today, BuzzFeed, ABC News, CBS News, CNN, NBC News, The Wall Street Journal
- Comments: The New York Times,

## Bugs
- Comments:
USA Today at Screen 28349 has error:
  - Traceback (most recent call last):
  File "get_fb_comments_from_fb.py", line 239, in <module>
    scrapeFacebookPageFeedComments(file_id, access_token)
  File "get_fb_comments_from_fb.py", line 168, in scrapeFacebookPageFeedComments
    reactions_data = reactions[comment_data[0]]
KeyError: u'10155892663085667_10155892720185667'

ABC News (19641)
  - HTTP Error 400: Bad Request
Error for URL https://graph.facebook.com/v2.9/86680728811_10156958124363812/comments/?limit=100&access_token=121368425347233|f19937bf4e14268bcc310b1deda8eba7&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=&after=OTcZD&fields=id,message,reactions.limit(0).summary(true),created_time,comments,from,attachment: 2018-03-09 23:51:12.618628
