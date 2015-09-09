# RAILS-Intro
##Course Exercise3
###Say Hello!


"Hello World" in RAILS

1. Create new Git branch for our changes
  1. git branch exercise3
  2. git checkout exercise3
2. Generate a controller, in the working directory blog run 'rails generate controller welcome index'
   * Note: For the rest of the course exercises a working directory of blog will be assumed when the rails cli is executed.
2. Take a look at your new controller and view: app/controllers/welcome_controller.rb, app/views/welcome/index.html.erb
3. Add Hellow World to the view
4. Start the RAILS server if it is not already running: 'rails s -b 0.0.0.0
5. Preview your app and add '/welcome/index' after the port number.
6. Git add and commit your changes


Set the root of our App to Welcome by adding a route.
1. Open config/routes.rb
2. Uncomment the line 'root 'welcome#index'
3. Go to the root of your app http://ruby-on-rails-xxxxxxx.nitrousapp.com:3000/
4. git commit your changes
5. git merge to branch to master
