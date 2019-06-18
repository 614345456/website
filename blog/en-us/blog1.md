# docker deploys MySQL images
After entering Linux, use the Docker command to download MySQL, such as:
```sh
Docker pull mysql: 5.7
` ` ` `
Running MySQL image
```sh
Docker run -- name MySQL 5.7 - P 3306: 3306 - e MYSQL_ROOT_PASSWORD = 123456 - D mysql: 5.7
` ` ` `
Note that the container name here is MySQL 5.7, the root user password of MySQL is 123456, the port mapping host 3306 to container 3306, the warehouse name MySQL and the label (label) only confirm the image to be specified, in fact, if there is only one MySQL, there is also a necessary label here.
