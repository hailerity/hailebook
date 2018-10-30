# Working with docker

## Build
```sh
sudo docker build -t <tag> .
```

## Run
```sh
sudo docker run -it <tag>
```
## Log in to container

## Use environment
example.env
```
RAILS_ENV=production
DATABASE_HOST=demo.com
```

And run with env
```sh
sudo docker run -d -p 3000:3000 --env-file ~/bin/eden_production.env -t eden-2
```
