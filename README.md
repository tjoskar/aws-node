
## Usage
```
$ docker run --rm tjoskar/awsnode:12 node -e "console.log('Hello 👋')"

$ docker run --rm --volume ${PWD}/dist:/build tjoskar/awsnode:12 npm ci --production
```

## Deploy

```
$ docker image build --tag tjoskar/awsnode:[node-version] .
$ docker push tjoskar/awsnode:[node-version]
```

