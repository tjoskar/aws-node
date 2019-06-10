
## Usage
```
$ docker run --rm tjoskar/awsnode:8 node -e "console.log('Hello 👋')"

$ docker run --rm --volume ${PWD}/dist:/build tjoskar/awsnode:10 npm install --production
```

## Deploy

```
$ docker image build --tag tjoskar/awsnode:[node-version] .
$ docker push tjoskar/awsnode:[node-version]
```

