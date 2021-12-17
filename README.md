# m1_rails_pg_compose


## Create rails app files
# docker-compose run --no-deps web rails new . --force --database=postgresql

## Build the image
# docker compose build

# Connect the db in config/database.yml
# default: &default
#   host: db
#   username: postgres
#   password: password


## Create db after docker compose up db
# docker-compose run web rake db:create
