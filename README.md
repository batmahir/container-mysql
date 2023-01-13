# container-mysql

1. In the docker-compose.yml file, replace yourpassword and yourdatabase with your desired root password and database name respectively.
2. In the terminal, navigate to your project directory and build the image by running the command docker-compose build.
3. Start the container by running the command docker-compose up -d to run it in detached mode.
4. Check the status of the container by running the command docker-compose ps. If the container is running, you should see it listed.
5. Verify that your MySQL server is running by connecting to it using the command docker-compose exec db mysql -uroot -p and enter your password that you have set on the compose file.
