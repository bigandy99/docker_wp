# docker_wp

Get going on WP docker suuuuuuper fast,

Steps to setup:
0. Install Docker Desktop and other basic stuff
1. Clone this repo
2. Run "docker-compose up"
3. Go to http://localhost to see WP running
4. Login to WP-Admin at http://localhost/wp-admin using u/p user/bitnami


More notes:
- This is a modified version of this recipe: https://hub.docker.com/r/bitnami/wordpress/
- This version mounts the instance's wp-content folder to your project root instead of using a Docker Volume
