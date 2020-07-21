# A Simple HTML Webpage using Httpd webserver

## Copy the Repository

```
Copy repo apache-httpd to docker machine . 
```

## Building Docker Image

```
$cd apache-httpd
$docker build -t testhttpd .
```

## Running the Container

```
$docker run -d -p 80:80 -name vinayhttp testhttpd
```

