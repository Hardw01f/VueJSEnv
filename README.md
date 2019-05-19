# VueJSEnv
The Dockerfile for develop of Vue.js


this Dockerfile is used another repository for build VueEnv

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

## Create New Progect(Vue Installed Test)

**Into container**

```
$ vue create myfirstvue

$ cd myfirstvue
$ npm run serve

```

access "http://localhost:9000"




