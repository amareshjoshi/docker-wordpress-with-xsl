# docker-wordpress-with-xsl
Docker configuration to add the XSL extension to the standard Docker WordPress image 
and setup a development environment with WordPress and MySQL
.
## To extend the WordPress image
In the folder containing the `Dockerfile` run:
```
docker build --tag wordpress_with_xsl .
```

## To create and run a Docker configuration for WordPress development

- Create folder `foo` for the project
- Copy the `.env` and `docker-compose.yml` files to `foo` and edit as needed
- Create a folder `foo/wp` to contain the WordPress source files
- Run: `docker-compose up -d`


