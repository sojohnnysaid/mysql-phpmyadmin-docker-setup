# 🐳 Docker MySQL & phpMyAdmin Setup 🚀

Welcome to the ultimate Docker setup for MySQL and phpMyAdmin! 🎉 Get your database and admin interface running with a few simple steps and dive right into managing your awesome databases with ease and joy! 🌟

## 📦 What's Inside?

- **MySQL 8.0**: The world's most popular open source database 🗃️.
- **phpMyAdmin**: A free software tool written in PHP, intended to handle the administration of MySQL over the Web 🌐.

## 🏁 Quick Start Guide

Follow these steps to get your MySQL database and phpMyAdmin running in no time:

### 1. Clone this Repository 📂

Clone or download this repository to get started.

```bash
git clone https://github.com/sojohnnysaid/mysql-phpmyadmin-docker-setup.git
cd mysql-phpmyadmin-docker-setup
```

2. Set Up Your Files 📁
Create a directory for shared files:

```bash
mkdir -p files_drop_zone
```

And one for phpMyAdmin configuration:

```bash
mkdir -p phpmyadmin_config
```

3. Fire Up Docker Compose 🚀
Run Docker Compose to start your services:

```bash
docker-compose up -d
```

4. Access Your Tools 🛠️

phpMyAdmin: http://localhost:8085
```
Server: db
Username: root
Password: rootpassword
```

MySQL: Connect via any standard MySQL client at localhost:3326.

5. Drop Files & Go! 📤
Simply drop any SQL dumps or files into the files_drop_zone directory, and they're ready to be accessed within both MySQL and phpMyAdmin!

🛠 Configuration
You can modify the docker-compose.yml to change environment variables like MySQL passwords or the phpMyAdmin port to suit your needs.

<img width="1013" alt="image" src="https://github.com/sojohnnysaid/mysql-phpmyadmin-docker-setup/assets/16521766/ab440d51-d516-40f5-9dbd-9dc30c4ea114">

