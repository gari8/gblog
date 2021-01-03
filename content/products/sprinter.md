---
title: "Sprinter"
date: 2021-01-02T20:15:43+09:00
draft: false
showtoc: true
tocopen: true
categories: [ "Products", "Go", "CLI" ]
---

### Get Started
```bash
    # binary is created on the go/bin directory.
    go get -u github.com/gari8/sprinter
```

### Command
```bash
    # Interactive interface launch.
    sprinter -n or -new
    
    # It show help
    sprinter -h or -help
```

### Conversation
```shell
    ? [1] Please enter the title of your application
    # enter your application name
    ? [2] Please select the database  [Use arrows to move, enter to select, type to filter]
      Postgres
    > Mysql
    # select database
    ? [3] Please select the architecture  [Use arrows to move, enter to select, type to filter]
    > Onion
      Clean
      MVC
    # select architecture
```

### Build server 
```shell
    docker-compose up --build
```

### Source-code

> https://github.com/gari8/sprinter


`Try using it !!!!😎`