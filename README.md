# docker_wp

Get going on WP docker suuuuuuper fast.....

Steps to setup:

0. Install Docker Desktop and other basic stuff
1. Clone this repo
2. Copy the contents into a new project repo/directory/whatever (i.e. don't push your new site back to this boilerplate!)
3. Make sure your local directory (or a parent directory) is listed in your Docker Desktop "File Sharing" list
4. Run "docker-compose up -d" (from your new directory) to build and start your containers
5. Go to http://localhost to see WP running
6. Login to WP-Admin at http://localhost/wp-admin using u/p user/bitnami
7. Run "docker-compose stop" to stop your containers from running in the background when you're not using them as stealing all your resources and making you wonder why your machine is running slow


More notes:
- This is a modified version of [this approach](https://hub.docker.com/r/bitnami/wordpress/)
- This version mounts the instance's wp-content folder to your project root instead of using a Docker Volume
- [More info local file sharing permissions](https://docs.docker.com/docker-for-mac/#file-sharing)
