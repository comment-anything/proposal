

`insert graphic at top`


## Project Title

Some possible titles:
 - Comment Anything
 - Rate and Comment any Website
 - Comment the Web
 - Comment URLs
 - Comments Everywhere


## Team members

...
Who will be in charge of each phase?


## Introduction


## Motivation

Comments are a valuable source of additional information.

On a news piece:
    - Omissions by writers
    - factual inaccuracies
    - conflicts of interest
    - supporting and opposing opinions

On a how-to article:
    - experiences applying it
    - additional information
    - tools
    - costs
    - overlooked steps

On a government article:
    - tips for navigating beauracracy
    - experiences dealing with an agency

On a business:
    - reviews
    - promotions of useful products
    - positive and negative experiences

Some possible readings to flesh out this section:

https://digitalcontentnext.org/blog/2020/03/05/comment-sections-arent-dead-yet/

https://theintercept.com/2017/12/18/comments-coral-project/

https://www.techdirt.com/2021/11/08/killing-website-comment-sections-wasnt-brilliant-move-many-newsroom-leaders-assumed/

https://medium.com/global-editors-network/why-news-websites-are-closing-their-comments-sections-ea31139c469d

https://mediaengagement.org/wp-content/uploads/2017/01/Comment-Section-Survey-Across-20-News-Sites.pdf

https://mediaengagement.org/research/comment-section-survey-across-20-news-sites/


## Objectives

1. Browser Extensions for Firefox and Chrome

An extension which adds a button to Firefox/Chrome. Clicking the button causes a comment section sidebar to appear. Users can log in to post comments. Anyone can view comments.

2. Back End serving comments, logging users in

A server running a back end parses requests, logs users in, and serves data to users which the Extension uses to populate the comment side bar

3. Bad comment identifier as a layer in the back end

AI word parsing or simple text searches can auto-flag dangerous comments. Additionally, users can report comments. 

4. Back End comment database

Comments stored and retrieved effeciently. Caching of popular comments. 

5. Moderation / Admin page

Reported and flagged comments are displayed. Moderator can review comments and de-flag and delete as appropriate.

6. Data Collection

We could track comment sentiment. Most engaged with comments.

7. Ad population

Build in a way to interleave ads with comments from the get-go?

### Implementation Techniques

- Flask API for Python back end

- SQLite for simplest Database application, or MySql server running on a separate process. Python MySQL connector, e.g., for backend to comm with db. SQLite easiest to implement, MySQL more scalable.

- JS/Typescript for the front-end (the extension). 
 - firefox api: https://support.mozilla.org/en-US/kb/deploying-firefox-with-extensions
  - chrome api: https://developer.chrome.com/docs/extensions/mv3/devguide/

- Sentiment analysis: https://techvidvan.com/tutorials/python-sentiment-analysis/


### Potential Users

- Journalists
- Researchers
- Armchair philosophers and political scientists
- Anyone looking for more information
- Any user of the internet


### Features and deliverables

1. Front end extensions
2. Back end server
3. Back end database


