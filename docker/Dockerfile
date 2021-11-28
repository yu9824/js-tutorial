FROM node:16.13.0-stretch

# Set timezone
ENV TZ="Asia/Tokyo"

# Install vim to use git and modify commit message by using it.
RUN apt-get update && apt-get install -y vim

# Add user
ARG user_name
RUN useradd -m ${user_name}
USER ${user_name}

ARG dir_name
ARG user_home_dir=/home/${user_name}
WORKDIR ${user_home_dir}/${dir_name}/