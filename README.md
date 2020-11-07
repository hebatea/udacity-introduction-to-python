# udacity-introduction-to-python

<h2>Python - Wikipedia Web Crawl Case Study</h2>
<p>You can add your first Wikipedia article link at <B>first_article</B> variable and at <B>target_url</B> you can add the target article and the code will: 
	<ul>
	<li>Show you the links' road from first article to last one if you keep clicking on the first link of each article.</li>
	<li>If the links more than max_step (which by default 25, and you can change it) the code will stop looking for.</li>
	</ul> 
</p>

<p>
	I have used those library:
	<ol>
		<li>The "<b>requests</b>" library which make html request to Wikipedia for read web pages content.</li>
		<li>The "<b>BeautifulSoup</b>" library to parse the html page and extract from it the first link in each page. The library documentation <a href="https://www.crummy.com/software/BeautifulSoup/bs4/doc/" title = "BeautifulSoup Documentation"> here</a></li>
		<li>The "<b>time</b>" library which make time between requests, because we do not want to overwhelm the server with request; we do not to be blocked</li>
	</ol>
</p>
