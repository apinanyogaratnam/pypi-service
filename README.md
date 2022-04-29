# PyPi Service

## Install a package
`pip3 install --index-url <url> <package> --trusted-host <host>`
```
pip3 install --index-url http://localhost:8080 utils --trusted-host localhost
```

## Upload a package
`twine upload --repository-url <url> <package>`
```
twine upload --repository-url http://localhost:8080 dist/*
```

## orchestrate container
```
docker-compose up -d --build --remove-orphans
```
