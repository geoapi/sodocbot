# StackOverflow Indexed topics Docs Chatbot Client Example

In this is example, we embed a RiveScript bot into a web page, i.e. to be
served from an Apache web server.

**Note:** this example requires an Elasticsearch web server. And since browsers have security
features preventing a local web page from accessing other local files, so if you
open `index.html` by double-clicking in your file browser it probably won't be
able to read the `.rive` files the bot needs.
If you want to make this works you can install Apache web server, upload this folder to /var/www and make sure you list the folder content as a website in /etc/apache2/sites-available by copying the 000-default.config and change the document root to the one of our bot.

 

And then visit <http://ip-address/> to load the
web client in your browser.

## Requierements: 
1- Node Js, 
2- NPM, 
3- babel-core, 
4- elasticsearch

## Brain file:
To change the brain for rivescript edit /var/www/web-client/elk.rive
