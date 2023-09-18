## Scrapping the top repositories for topics on Github##

💻 Web scraping is the process of extracting and parsing data from websites in an automated fashion using a computer program. It’s a useful technique for creating datasets for research and learning. 
Its a way to automatically gather information from websites.

Imagine you have a big library with lots of books. Instead of reading each book one by one ,web scrapping helps you quickly find specific information you're intrested in.

Here's how it works 

A Computer Program(like robot) visits a website and looks atthe content , just a person would . But instead of reading and remembering everything,it picks out specific pieces of information like names, prices, descriptions and stores them in a neat list.

This is very useful for all kinds of things like comparing prices of products,collecting data from research,keeping track of new articles.

Here are the steps we’ll follow to build a web scraping project from scratch:
✅ Pick a website and identify the information to be scraped into a CSV file
💾 Use the requests library to download web pages from the site programmatically
💬 Use Beautiful Soup to parse and extract information from web pages
📝 Create well-formatted CSV file(s) with the extracted information

 Outline

#We are going to scrape the page github.com/topics
# We will get a list of topics and each topic we'll get topictitle,topic page URL and topic description
#For each topic we'll get top 25 repositoriesin the topic from the topic page
#For each repositority we'll grap the repo name,user name,stars and repo URL
#For each topic we'll create a CSV file in the following format:
#Repo name	User name	Stars	Repo URL		
#three.js	mrdoob	94500	https://github.com/mrdoob/three.js		
#eact-three-fiber	pmndrs	23800	https://github.com/pmndrs/react-three-fiber		

