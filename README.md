# RAILS-Intro
##Course Exercise3
###Lets merge to master and push to Heroku!
1. heroku login
1. heroku create, note app name.
1. Find DB info, 'heroku config'
1. Update DB configuration
1. Enable serving static files
  1. Add gem rails_12factor to Gemfile
  1. Run 'bundle install' to update Gemfile.lock
1. Git commit DB confioguration changes, Gemfile and Gemfile.lock
1. Git merge working branch to master
1. Deploy to Heroku 'git push heroku master'
2. Veriy connection to database, 'heroku run rake db:migrate'
1. Verify app app_name.herokuapp.com
