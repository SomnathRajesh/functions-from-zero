# functions-from-zero
[![Python application test with github Actions](https://github.com/SomnathRajesh/functions-from-zero/actions/workflows/main.yml/badge.svg)](https://github.com/SomnathRajesh/functions-from-zero/actions/workflows/main.yml)

# To Call Microservice

curl -X 'POST' \
  'https://verbose-parakeet-pjrpv7vrx94v3r6g-8080.app.github.dev/wiki' \
  -H 'accept: application/json' \
  -H 'Content-Type: application/json' \
  -d '{
  "name": "Microsoft"
}'

### Build container
`docker build .`
`docker image ls`

### Run container

`docker run -p 127.0.0.1:8080:8080 6728663e8cca`

### Invoke POST Request

run `invoke.sh`