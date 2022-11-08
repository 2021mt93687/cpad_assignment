# cpad_assignment

To setup database on local use following command:

docker run -d -p 8529:8529 --name Assignment -e ARANGO_ROOT_PASSWORD=root -v <path>/_db:/var/lib/arangodb3 arangodb/arangodb:3.10.0

Prerequisite:

Docker desktop needs to be installed
