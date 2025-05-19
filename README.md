# docker-ionic-capacitor

🐳 Docker image for building Ionic apps with Capacitor. 

## How to use this image

<!-- ### Pull image

Pull from Docker Registry:  
`docker pull robingenz/ionic-capacitor` -->

### Build image

Build from GitHub:  
```
docker build -t robingenz/ionic-capacitor https://github.com/robingenz/docker-ionic-capacitor.git#main
```

Available build arguments:  

- JAVA_VERSION (Default: `17`)
- NODEJS_VERSION (Default: `20`)
- ANDROID_SDK_VERSION (Default: `11076708`)
- ANDROID_BUILD_TOOLS_VERSION (Default: `34.0.0`)
- ANDROID_PLATFORMS_VERSION (Default: `34`)
- GRADLE_VERSION (Default: `8.2.1`)
- IONIC_VERSION (Default: `7.2.0`)
- CAPACITOR_VERSION (Default: `6.0.0`)

### Run image

Run the docker image:  
```
docker run -it robingenz/ionic-capacitor bash
```

## Questions / Issues

If you got any questions or problems using the image, please visit my [GitHub Repository](https://github.com/robingenz/docker-ionic-capacitor) and write an issue.

If build fail on mac m1/m2 with qemu x84_64 error add '"runArgs": ["--platform=linux/amd64"]' to devcontainer.json in vscode.
