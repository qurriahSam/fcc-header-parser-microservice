# Request Header Parser Microservice for FCC

## About

This is a project developed as part of the [Request Header Parser challenge](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/request-header-parser-microservice) for the freeCodeCamp API and Microservice certification. The project represents a robust and sophisticated solution that enables users to easily retrieve and view key information about their IP address, language, and software configuration. It was built based on the boilerplate available [here](https://github.com/freeCodeCamp/boilerplate-project-headerparser/).

## Endpoints:

| Endpoints         | Description                                                                                      |
| ----------------- | ------------------------------------------------------------------------------------------------ |
| GET `/api/whoami` | Return an object with IP Address and information from `accept-language` and `user-agent` headers |

#### Example usage:

- https://header-parser-hupd.onrender.com/api/whoami

#### Example output:

- `{"ipaddress":"159.20.14.100","language":"en-US,en;q=0.5", "software":"Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:50.0) Gecko/20100101 Firefox/50.0"}`

## How to use:

Just run on terminal:

```
npm install
npm start
```
