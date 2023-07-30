# Kerakend Example

This is an example project for using multiple Kerakend services to create a Docker-based web application.

## Installation and Setup

To use this project, you need to have Docker installed. Then, clone the project using the following command:

```
git clone https://github.com/amrmrp/kerakend-example.git
```

Then, you can run the application using the following command:

```
docker-compose up -d
```

You can then access the application via a web browser at `http://localhost:8080/fakeApi`.

## Services

This project uses several Kerakend services, including:

- **Database**: Postgres database is used for storing data.
- **Web Server**: Gunicorn web server and WSGI web interface are used to create a networked web application.
- **Message Queue**: RabbitMQ is used to implement a secure message queue for processing scheduled forecasts.

## Contributing

If you would like to contribute to this project, you can simply clone the project, make your changes, and then push them back to the main project using `git push`. Additionally, you can report issues and bugs with the project using the Issue Tracker.

## License

This project is licensed under the MIT License. For more information about this license, please refer to the `LICENSE` file.
