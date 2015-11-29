# Welcome on wall of anonimous kindness
## A simple Heroku + Sinatra + Active record web app
# https://sleepy-fortress-1212.herokuapp.com

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
