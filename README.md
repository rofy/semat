== README

When a delete comes in for a item that is new, that means a mistake was made. Just delete it, don't mark it as delete.






Please feel free to use a different markup language if you do not plan to run
<tt>rake doc:app</tt>.

## Installing
$ echo "RACK_ENV=development" >>.env
$ echo "PORT=3000" >> .env
foreman start


rake assets:precompile RAILS_ENV=production



 http://localhost:3000/api/v1/simple_alphas.json



## Setup
rake semat:import_alpha_cards

rails console
AdminUser.create!(:email => 'admin@example.com', :password => 'password', :password_confirmation => 'password')


## Admin on production
heroku run rails console
git push heroku master
heroku pgbackups:capture --expire --app semat
heroku run rake db:migrate --app semat

## Initialize on production
heroku run rake semat:import_alpha_cards


## Great Tools
http://jsonlint.com/
Excellent Tutorial on Android and Rails: http://lucatironi.github.io/tutorial/2012/10/15/ruby_rails_android_app_authentication_devise_tutorial_part_one/


## Copy production database to local machine
heroku pg:pull HEROKU_POSTGRESQL_AMBER_URL SEMAT_heroku --app semat
