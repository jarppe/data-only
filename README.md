# Minimal docker image for docker-compose compatible data-only containers

While you can create pure data-only containers, using them with
docker-compose is not trivial. The docker-compose requires that the
container has some executable in it.

This image contains a statically linked binary `true` that just exists
immediattly with status 0.

The image size is 20.1kB.


# License

Copyright © 2019 Jarppe Länsiö

Distributed under the Eclipse Public License either version 1.0 or (at your option) any later version.
