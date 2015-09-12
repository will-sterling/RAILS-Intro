# RAILS-Intro
##Course Exercise2
1. Configure Git
  1. Copy your GitHub SSH key pair to your Nitrious.io workspace
  1. git config --global user.email "you@example.com"
  1. git config --global user.name "Your Name"
1. Fork blog repo - https://github.com/will-sterling/blog
1. Clone your copy of blog repo to Nitrous container.
1. Change into blog directory
1. Create new working branch to make changes in.
  1. create new branch exercise2
  1. checkout branch exercise2
1. Change directories back up to blog's parent directory.
1. Create a new RAILS App!
  1. rails new blog -d postgresql
  1. change into blog directory
  1. rails s -b 0.0.0
  1. Click preview select port 3000
1. Looks good?  Commit your changes!
  1. git add -A
  1. git commit -m "Initial commit"
  1. Checkout master branch, merge branch exercise2 to master
