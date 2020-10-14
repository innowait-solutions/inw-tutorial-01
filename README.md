#Innowait Solutions Tutorial 01
##A-Z Coming Soon Website

Welcome to Innowait Solutions support docs for our tutorials.

Let's create a website!

###Template
* Template for the Coming Soon Website can be found in `template/` folder!
* You can amend images in `template/images` folder including backgrounds and logo!
* Placeholders in index.html which you can just "Find & Replace":
  * `%COMPANY_NAME%` - Your Company Name
  * `%YEAR%` - Current Year
  * `%FACEBOOK_URL%` - URL to your Facebook Profile
  * `%TWITTER_URL%` - URL to your Twitter Profile
  * `%YOUTUBE_URL%` - URL to your YouTube Profile
  * `%INSTAGRAM_URL%` - URL to your Instagram Profile
* Current main color is #700000 in `main.css`, again you can just "Find & Replace" with the color which matches your brand!
* To change countdown - just go to `template/js/main.js` on line 60 you will see the date, change it to whatever you want (in the same format) and countdown will pick the change!

###Server Configuration
* Install nginx on your server using command (for Ubuntu):
```sudo apt-get install nginx```

* Website configuration file has to sit under `/etc/nginx/sites-enabled/%YOUR-NAME%`
* To reload configuration for nginx use command
```sudo service nginx reload```
* NGINX Configuration to listen for requests on port 80 and direct to your html website can be found in a `server/website` file.
