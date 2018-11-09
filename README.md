# Docker Mongo DB bootstrap

### Requirements

* docker-compose (version 3.7)

### Before first run

Create a .env file in the project root directory
```bash
$ touch .env
```

Copy the contents of the .env.dist file and replace values accordingly
```bash
$ cat .env.dist > .env
```

### Running the container

Run command: *(user id prefix is to avoid running as root)*
```bash
$ docker-compose up -d
```