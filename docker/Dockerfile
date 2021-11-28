FROM node:16.13.0-stretch

# Set timezone
ENV TZ="Asia/Tokyo"

# Add user
ARG user_name
RUN useradd -m ${user_name}
USER ${user_name}

ARG dir_name
ARG user_home_dir=/home/${user_name}
WORKDIR ${user_home_dir}/${dir_name}/