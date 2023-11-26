# Architecture

## About

![](assets/about.drawio.svg)

## Structure

### Containers (Develop)

![](assets/dev-containers.drawio.svg)

### Files

```
authenticator
|
+-- .devcontainer
|   |
|   +-- devcontainer.json
|
+-- server
|   |
|   +-- Laravel Code
|
+-- client
|   |
|   +-- Vue Code
|
+-- build
|   |
|   +-- server
|   |   |
|   |   +-- Dockerfile
|   |
|   +-- client
|   |   |
|   |   +-- Docekrfile
|   |
|   +-- .env
|   |
|   +-- docker-compoer.yml
|
+-- server.code-workspace   // VSCode Workspace for Server
|
+-- client.code-workspace   // VSCode Workspace for Client
|
+-- docs
    |
    +-- assets
    |   |
    |   +-- *.svg
    |
    +-- *.md
```
