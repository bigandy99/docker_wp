# docker_wp

Get going on WP docker suuuuuuper fast.....

Steps to setup:
0. Install Docker Desktop and other basic stuff
1. Clone this repo
2. Make sure your local dev directory (or a parent directory) is listed in your Docker Desktop "File Sharing" list
3. Run "docker-compose up -d" to build and start your containers
4. Go to http://localhost to see WP running
5. Login to WP-Admin at http://localhost/wp-admin using u/p user/bitnami
6. Run "docker-compose stop" to stop your containers from running in the background when you're not using them as stealing all your resources and making you wonder why your machine is running slow


More notes:
- This is a modified version of [this approach](https://hub.docker.com/r/bitnami/wordpress/)
- This version mounts the instance's wp-content folder to your project root instead of using a Docker Volume
- [More info local file sharing permissions](https://docs.docker.com/docker-for-mac/#file-sharing)
