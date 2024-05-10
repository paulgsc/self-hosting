# self-hosting

I'm using this to self host on a local nixos server.

# Docker nice to know

Docker commmands that occur frequently:

- listing images
- deleting images
- building containers
- running containers

  List all running containers:

  ```
  docker ps
  ```

  Stop containers running:

  ```
  docker stop CONTAINER_ID
  ```

  Remove containers:

  ```
  docker rm CONTAINER_ID
  ```

  Remove all dangling images (images that are not being used by any container) from your system.:

  ```
  docker image prune --all
  ```
