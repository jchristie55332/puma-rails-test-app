Application to recreate the bug around `log_requests` inside puma config

This is a very basic generated rails application

To run:

`bundle install`

then

`bundle exec rails s`

and access

`http://localhost:3000`

Application logging level has been set to error so no app logs are seen

When `log_requests` is toggled in `./config/puma.rb` there is no change as a result of the forced quiet
