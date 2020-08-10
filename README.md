# wikipedia-simple-webcrawler

Objectives : 
Open an article on the web
Find the first link in the article
Follow the link
Repeat this process until we reach the Philosophy article, or get stuck in an article cycle.

Start with a random wikipedia page,and get the first link on the page which is part of the (html)'div' section that contains the article's body,get the direct children of 'div' that are paragraphs. Find the first anchor tag that's a direct child of a paragraph, build a full url from the relative article_link url.
function1: crawl(start_url,target_url,max_steps)
Create  a list by appending these article links , keep checking the list for a repeated link or reaching the max no of links or the target link,in any of these cases the loop should stop
