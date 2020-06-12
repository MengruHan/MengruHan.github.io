Enter the following command to check the version of gem,ruby
# gem -v
# ruby -v
check source address
#gem sources -l
remove sources address
#sudo gem sources --remove http://rubygems.org/
add new address
#sudo gem sources -add 

Gem
update Gem
#gem update —system

check gem version
#gem -v
Ruby
Install RVM (rvm is Ruby's version manager, rvm allows you to have multiple versions of Ruby, and between them Switch freely.)
#curl -L get.rvm.io | bash -s stable
#source ~/.rvm/scripts/rvm
Then input
#rvm -v 

Install rvm
List the versions of ruby that can be installed
# Rvm list know
Installing a ruby version
#rvm install 2.7.0
Setting  default
#rvm use 2.7.0 —default
View installed ruby 
#rvm list
Uninstall a version of ruby that is already installed
#rvm remove 2.4.1


Install
#Sudo gem install Jekyll
Check version 
#Jekyll -v


Creating your blog site with Jekyll
#Jekyll new my blog
#cd myblog
update some files
#bundle install

#jekyll serve/ bundle exec jekyll serve
#http://127.0.0.1:4000/



Create a new repo
#mengruhan.github.io
#git status
#Git init
Change _config.yml
#git add  .
#git commit -m ‘blog’

Then push the code into the repo.
# git remote add origin https://github.com/MengruHan/mengruhan.github.io.git
#Git push origin master
#jekyll serve/ bundle exec jekyll serve
#http://127.0.0.1:4000/
Note：Make sure there are no jekyll services in other directories before starting.  
#ps aux|grep jekyll
#sudo kill -9 xx





