# Yappa Woosh App Docker Image

## Usage

Add the following to your docker-compose.yml file:

```
app:
    image: yappabe/woosh-app
    volumes:
        - .:/var/www/app
        - ../libs:/var/www/libs
    tty: true
```
