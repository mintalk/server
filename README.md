# Mintalk


## Server

### Running
> Add -h to show the full usage.

~~~
go run .
~~~

### Configuration

The configuration file is located at `config.yaml`.

Example configuration:

~~~
database: user:pass@tcp(127.0.0.1:3306)/mintalk?charset=utf8mb4&parseTime=True&loc=Local
host: localhost:8000
session_lifetime: 1440
cleanup_interval: 5
~~~

### Commands

When running the server, you can input some commands.

[List of commands](COMMANDS.md)
