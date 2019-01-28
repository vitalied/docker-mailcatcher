![Docker pulls](https://img.shields.io/docker/pulls/vitalied/mailcatcher.svg?style=flat)

# Mailcatcher Docker Image

This adds mailcatcher and makes it available on on port 1080.

## Usage

Add the following to your docker-compose.yml file:

```YAML
mailcatcher:
    image: vitalied/mailcatcher
    ports:
        - 1025:1025
        - 1080:1080
```

You can now use mailcatcher as an smtp server, simply use 'mailcatcher', or whatever you named this container as host on port 1025.

## References
* http://mailcatcher.me/
