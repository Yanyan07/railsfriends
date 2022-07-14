# README

rails s 
# rails can generate all kinds of things: controller in home, page index
rails generate controller home index

rails routes (check all routes)

# create new file
cmd + s --> change file name

# <%= %> : put it on screen
  <%  %> : not put it on screen

# create table: friends, and what we want in the table
rails g scaffold friends first_name:string last_name:string email:string phone:string twitter:string 
# push data to database
rails db:migrate

# rubygems.org --> devise --> gemfile copy --> go to our gemfile --> paste
# terminal: bundle install 
# homepage(github) --> 
# terminal: rails generate devise:install
# development.rb --> config.action_mailer.default_url_options = { host: 'localhost', port: 3000 }  
# terminal: rails g devise:views
# terminal: rails generate devise user --> rails db:migrate --> rails routes

# home/_header.html.erb --> 
#       <li class="nav-item">
#         <%= link_to "Sign Out", destroy_user_session_path, method: :delete, class:"nav-link" %>
#       </li>
# 

### Style Device Views

### Association
# rails g migration add_user_id_to_friends user_id:integer:index
# rails db:migrate
# <% if friend.user == current_user %>

### Style Modifications

### Git Github
# git add . (add everything in our project to our repository)
# git commit -m 'initial commit' (save code to our local repository)
# (push code to the third party of website)
# mkdir ~/.ssh 
# cd ~/.ssh
# ssh-keygen.exe
# enter
# passphrase: enter  enter
# ls (two files)
# cat id_rsa.pub 
# 




