#Chris's Reading List

A reading list rails app. Built following the Rails For Zombies 2 [Soup to Bits](https://github.com/codeschool/RFZ2SoupToBits) videos but using [Postgres](http://postgresguide.com/) for the database so it can run on Heroku.

## Deploying to Heroku

```sh
$ heroku create
$ git push heroku master
$ heroku run rake db:migrate
$ heroku open
```

## Running locally

To run locally, make sure you have Postgres installed and running. From the command line run:

```sh
$ rails server
```


## Documentation

For more information about using Ruby on Heroku, see these Dev Center articles:

- [Ruby on Heroku](https://devcenter.heroku.com/categories/ruby)

---
