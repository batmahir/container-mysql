# container-mysql

1. Clone the project
2. Ensure there is directory called data in your project directory that will be used as a volume to store the data for your MySQL container
3. In the docker-compose.yml file, replace yourpassword and yourdatabase with your desired root password and database name respectively.
4. Copy the .env.example to .env and update your database root password
5. `docker-compose build .` or `docker compose build .` 
6. Start the container by running the command `docker-compose up -d` or `docker compose up -d` to run it in detached (background) mode.
7. Check the status of the container by running the command `docker-compose ps` or `docker compose ps`. If the container is running, you should see it listed.
8. Verify that your MySQL server is running by connecting to it using the command `docker-compose exec db mysql -uroot -p` `docker compose exec db mysql -uroot -p`  and enter your password that you have set on the compose file.

