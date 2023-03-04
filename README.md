# Tutorial Symfony project to PROD

*Inspired from YoanDev tutorial: [Du DEV à la PROD en 20 MINUTES (avec Symfony, Docker et Hidora) 🔥](https://youtu.be/CK_SqfxAjuE "Du DEV à la PROD en 20 MINUTES (avec Symfony, Docker et Hidora) 🔥").*

Docker Image: [mushuledragon/hellokaamelott](https://hub.docker.com/r/mushuledragon/hellokaamelott)

## Dockerization

- Create Dockerfile
- Add apache.conf file to container
- Add docker ecex script to run the serve after container build
- Create Makefile
- Build Docker container `make docker-build`
- Push container to DockerHub `make docker-push`
- Pull container `docker pull mushuledragon/hellokaamelott`
- Run container `docer run -d -P 80:80 mushuledragon/hellokaamelott`

Access to the website [here](localhost:80)