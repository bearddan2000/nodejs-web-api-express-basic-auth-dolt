# nodejs-web-api-express-basic-auth-dolt

## Description
A POC project for expressjs api that uses basic authentication. The api then connects to a dolt database.

| username | password |
| -------- | -------- |
| *root* | * * |

## Tech stack
- expressjs
- dolt

## Docker stack
- node:latest
- dolthub/dolt-sql-server

## To run
`sudo ./install.sh -u`
http://localhost/dogs

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- https://www.docker.com/blog/getting-started-with-docker-using-node-jspart-i/
- https://www.tutorialspoint.com/nodejs/nodejs_first_application.htm
