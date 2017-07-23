# Exercise for a Loadbalanced WebServer setup

The company you work for has a very popular (but fictitious) website called GeeksTimeout.com. 

It is an online community where geeks from all over the world come to share light banter and jokes
about their experiences at work. From secret crushes, difficult managers to non-tech savvy colleagues.

The site has grown in popularity so much that the current web server architecture is struggling to
handle the traffic volume. In the recent months, the web server crashes at least once every four days.

Everyone in higher management has agreed that a new web infrastructure needs to be setup to better
serve the needs of GeeksTimeout.com and its users. Everyone also agrees that you are 
the most suitable person for the task.  

Key features of the website to consider: 
- 6500 daily unique visitors
- The site is multilingual and supports the following languages: English, French, German, Spanish, Swedish.
- English visitors come from the UK, US, Canada, South Africa, Australia etc.
- French visitors come from France, Canada, Switzerland etc.
- German visitors come from Germany, Switzerland, Austria
- Spanish visitors come from Spain, Argentina, Mexico, Chile etc.
- The site does not use a CDN.

The new web architecture should:
- Maximize the site's performance without the use of a CDN.
- Provide maximum availability. 
- Provide a caching mechanism that allows for Spanish and Argentinian visitors to receive the same content, for German and Austrian visitors to receive the same content etc.

Your task is to create three virtual machines that are able to host a website with the requirements above.

When completed please export all three of the machines so that we can review and upload to a BitBucket or GitHub repo

Please do not think you have to fix everything on here or spend lots of time on this part spend no more that two hours there will be time afterwards to explain your thinking on a call with us.
