# vuedockerapp

This is sample repository for vue doacker app.

To Build the docker image.
```
    docker build -t dockervue .
```

To run the image in container
```
    docker run -p 8002:80 -it --name dockerizedvue dockervue
```
## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
