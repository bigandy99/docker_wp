# docker_wp

Get going on WP docker suuuuuuper fast,

Steps to setup:
0. Install Docker Desktop and other basic stuff
1. Clone this repo
2. Run "docker-compose up -d" to build and start your containers
3. Go to http://localhost to see WP running
4. Login to WP-Admin at http://localhost/wp-admin using u/p user/bitnami
5. Run "docker-compose stop" to stop your containers from running in the background when you're not using them as stealing all your resources and making you wonder why your machine is running slow


More notes:
- This is a modified version of this recipe: https://hub.docker.com/r/bitnami/wordpress/
- This version mounts the instance's wp-content folder to your project root instead of using a Docker Volume
