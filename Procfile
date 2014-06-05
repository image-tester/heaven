web: bundle exec unicorn -p $PORT -c config/unicorn.rb
worker: bundle exec rake resque:work QUEUE=* TERM_CHILD=1 RESQUE_TERM_TIMEOUT=120
