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

rake cucumber
bundle exec cucumber features/merge_article.feature
bundle exec cucumber features/merge_article_merging.feature
bundle exec cucumber features/create_category.feature

rake spec
rspec -p "spec/models/article_spec.rb"
rspec -p "spec/controllers/admin/content_controller_spec.rb"

## HW 1-2


## HW 2
