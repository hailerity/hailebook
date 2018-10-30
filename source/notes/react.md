# Create reactjs client app

1. Create app using create-react-app
```bash
  create-react-app saiden
```

2. Eject
```bash
  yarn eject
```

3. Run project
```bash
  yarn start
```

4. Create node server to serve


5. Create Dockerfile
```
FROM node
RUN mkdir -p /saiden
ADD . /saiden
WORKDIR /saiden
RUN cd /saiden
RUN yarn install
RUN yarn build
CMD ["node", "server"]
```

6. Build docker image and run it


7. More to do

+ Install redux
+ Install react router
+ Install hot loader
+ Install semantic ui
+ Install logger for server
+ Install restful client

7. Install logger for node server

Use [morgan](https://github.com/expressjs/morgan)

8. Setup redux


# Nice Articles
1. https://medium.com/@luigiplr/react-redux-react-router-4-code-splitting-w-rxjs-webpack-32eabedf0e9
