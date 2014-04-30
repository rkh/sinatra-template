Minimal Sinatra template, as requested on Twitter.

Run:

    bundle install
    foreman start

Deploy to heroku:

    heroku create --stack cedar
    heroku config:add RACK_ENV=production
    git push heroku master
