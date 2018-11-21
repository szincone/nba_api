# nba_api :basketball:
NBA API that scrapes [basketball-reference](basketball-reference.com) to seed the API data.

## how to use
- Fork and clone.
- cd into `api` and run `knex migrate:latest` to create db
- while in `api`, run `knex seed:run` to seed the db w/ the scraper data
- still inside `api`, run `yarn start` to start the API
- API will be running on `localhost:9000/api/players`

## scraper
- Cheerio
- Cheerio-TableParser
- Request-Promise

## back-end
- Node.js
- Express
- Knex
- SQLite

## authors
- Sawyer Zincone -_intial work_- [szincone](https://github.com/szincone)