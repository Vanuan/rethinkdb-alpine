RethinkDB Alpine
----------------

* [Docker Hub](https://hub.docker.com/r/vanuan/rethinkdb-alpine/)

# How to use

1. Create docker-compose file:

      rethinkdb:
        image: 'Vanuan/rethinkdb-alpine'
        ports:
          - 127.0.0.1:9000:8080

2. Run 'docker-compose up'

3. Open http://127.0.0.1:9000
