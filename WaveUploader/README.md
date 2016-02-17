# Wave Uploader

## To start the application

from the `WaveUploader` directory:

1. `bundle install`
1. `bundle exec rake db:create && bundle exec rake db:migrate`
1. `bundle exec rails s` 

*NOTE*: this will start Rails in development mode. To run the application in production mode, instead run:

`RAILS_ENV=production bundle exec rails s`

## To use the application

1. point your browser to `localhost:3000`