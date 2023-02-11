FROM node:17.0.1

# node may come with an older version of npm. Ensure we have a specific npm.
RUN npm install -g npm@8.1.0


################################################################################
# Install prerequisites
RUN apt-get update
RUN apt-get install -y \
  lsb-release \
  curl
