# Cayenne

## Setup Rails 5 as described here : 

https://gorails.com/setup/osx/10.12-sierra


## Setup 

- Install rails 5.0.1 

==> gem install rails -v 5.0.1

==> rbenv rehash

==> rails -v
Rails 5.0.1


==> rails new cayenne -d mysql


# If you setup MySQL or Postgres with a username/password, modify the
# config/database.yml file to contain the username/password that you specified

# Create the database
rake db:create

rails server
