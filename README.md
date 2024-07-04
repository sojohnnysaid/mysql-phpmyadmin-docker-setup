# Quickstart
Download the docker-compose.yml
run `docker-compose up -d` in the directory where you downloaded the file

# Purpose
This is a great POC tool when you want to showcase a quick and dirty implementation and share it with other team members. This is just the base image, and I'd recommend you add additional queries and copy in sample data to build out a fully working database an end user can explore from the GUI.

# mysql-phpmyadmin-docker-setup
MySQL and phpMyAdmin server quickstart on Docker


Here are the creds:

environment:
      
      MYSQL_ROOT_PASSWORD: rootpassword
      
      MYSQL_DATABASE: mydb
      
      MYSQL_USER: user
      
      MYSQL_PASSWORD: userpassword

Use root for full permissions

localhost port 8080 on your browser to navigate the database using the phpmyadmin GUI 🎉
