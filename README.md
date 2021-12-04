### yeet-docker

------------
Docker repository for the Yeet application. Comprising the Yeet app and YeetBot.

First things first, navigate into a directory of your choice on your local system and clone this repository by running 

```
git clone https://github.com/olamileke/yeet-docker.git
```

When cloning is complete, navigate into the docker directory by running

```
cd yeet-docker
```
Clone the Yeet and YeetBot repositories  by running the following commands

```
git clone https://github.com/olamileke/yeet.git
```
```
git clone https://github.com/olamileke/yeetbot.git
```
Remember to make sure that the relevant environment variables are set in the yeet and yeetbot applications in the .env file. Still in the /yeet-docker folder create the certbot, certbot-etc, certbot-var and mysql folders by running the following command.
```
mkdir certbot certbot-etc certbot-var mysql
```
