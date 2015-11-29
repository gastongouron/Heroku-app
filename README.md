# Wall of Whatever
## A simple Heroku + Sinatra + Active record web app.

**Problem Space description**

Wall of Whatever is a simple web form storing users submitted text on a web server and displaying these in a forum-like style. Here, you can add whatever and everyone else will see it. That's it.

**List of requirements**

The schema design is very simple here, I was more interested in trying to make something live on the web for this 2nd version of the design-your-own challenge.

# To see it live
-> https://sleepy-fortress-1212.herokuapp.com

# To run the app / deploy on heroku
-> bundle install (after you make sure Gemfile.lock is up-to-date)
-> commit changes to git
-> run 'heroku create' on shell
-> git push 'heroku master'

# To monitor / reset DB
-> Log on your account on heroku.com
-> if you reset db, you will have to ‘heroku run rake db:migrate‘

# open your app site
-> 'heroku open'
