# docker-rclone
Docker container of rclone

Please see https://github.com/rclone/rclone for all content-related issues. This repo is only for the containerisation. 

## Instructions

- Download repo
- Configure docker-compose.yml
- Execute: docker-compose up -d
- Option 1) CLI - Execute: ./rclone (on host, requires altered entrypoint)
- Option 2) GUI - Go to http://docker:5572 (requires default entrypoint + password in docker-compose.yml)
