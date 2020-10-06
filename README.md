# TS3AudioBot-Docker

![Docker](https://github.com/CookieCr2nk/TS3AudioBot-Docker/workflows/Docker/badge.svg?branch=master)

This is the TS3AudioBot in a Docker Container based on Debian Buster with dotnet runtime 3.1

# Usage / Parameters

* For using this Dockerfile/Dockerimage you need knowledge in Docker. For Bugs please create an issue.
* Docker Run: ```docker run -p 58913:58913 --name ts3bot -v ts3bot_data:/opt/TS3AudioBot -d ghcr.io/cookiecr2nk/ts3audiobot:latest```

* Docker Build:  ```docker build -f Dockerfile . ```

# Contribution

Feel free to make an feature request or an pull request.

# Ressources

This Dockerfile uses minimal ressources.

# TS3AudioBot Version

This image was build on develop_linux_x64 with version 0.12.0-alpha.43
