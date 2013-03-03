# saas-CS169.2x

saas-CS169.2x

## HW 1-1
git clone git@github.com:ilyapalkin/typo
cd typo
bundle install -- without production
rake db:migrate
rake db:seed
rake spec
rake cucumber

heroku login
heroku create typo-hw1
git push heroku master
heroku run rake db:migrate
heroku run rake db:seed

## HW 1-2


## HW 2
