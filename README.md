# docker-ionic-capacitor

🐳 Docker image for building Ionic apps with Capacitor. 

## How to use this image

<!-- ### Pull image

Pull from Docker Registry:  
`docker pull robingenz/ionic-capacitor` -->

### Build image

Build from GitHub:  
```
docker build -t robingenz/ionic-capacitor github.com/robingenz/docker-ionic-capacitor
```

Available build arguments:  

- JAVA_VERSION
- NODEJS_VERSION
- ANDROID_SDK_VERSION
- ANDROID_BUILD_TOOLS_VERSION
- ANDROID_PLATFORMS_VERSION
- GRADLE_VERSION

### Run image

Run the docker image:  
```
docker run -it robingenz/ionic-capacitor bash
```

## Questions / Issues

If you got any questions or problems using the image, please visit my [GitHub Repository](https://github.com/robingenz/docker-ionic-capacitor) and write an issue.
