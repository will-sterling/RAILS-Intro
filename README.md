# RAILS-Intro
##Course Exercise3
###Lets push to Heroku!
1. heroku login
1. heroku create, note app name.
1. Update DB configuration
  1. Edit config/database.yml
  2. Go to the bottom of the file and replace the production config with:
  ```yaml
  production:
  <<: *default
  url: <%= ENV['DATABASE_URL'] %>
  ```
1. Enable serving static files
  1. Add gem rails_12factor to Gemfile
  1. Run 'bundle install' to update Gemfile.lock
1. Git add and commit DB configuration changes, Gemfile and Gemfile.lock to master
1. Deploy to Heroku 'git push heroku master'
2. Veriy connection to database, 'heroku run rake db:migrate'
1. Verify app https://app_name.herokuapp.com
  * if you forgot your application name you can get the name and URL by running 'heroku apps:info'
