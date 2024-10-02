# syntax=docker/dockerfile:1
FROM alpine
WORKDIR /src
RUN --mount=target=. \
  make REVISION=$(git rev-parse HEAD) build


  # Command

#   docker build \
#   --build-arg BUILDKIT_CONTEXT_KEEP_GIT_DIR=1
#   https://github.com/user/myrepo.git#main

# Not working when I tried