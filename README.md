# VueJSEnv
the Dockerfile for develop of Vue.js

### Versions

- centos 7
- npm 6.4.1
- node v8.16.0
- vue 3.7.0

## build and Run

```

$ docker build -t NAME:TAG .

$ docker run -p 9000:8080 -it CONTAINERNAME:TAG /bin/zsh 

```


## Create New Progect

**Into container**

```
$ vue create myfirstvue

$ cd myfirstvue
$ npm run serve

```


## Access Vue.js

http://localhost:9000




