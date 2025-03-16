# Request Header Parser Microservice

This project implements a simple API that returns client (such as browser) details, including remote IP address of the request, languages accepted, and user-agent info.

NB: This project builds on boilerplate code provided for the [Request Header Parser Microservice](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/request-header-parser-microservice).

## API Endpoint

`/api/whoami:` Returns a JSON object with `ipaddress`, `language`, and `software` keys, representing the remote IP address of the request, languages accepted by the client, and the user-agent, respectively.

## Example Use Case

`/api/whoami` returns
```
{
    "ipaddress":"159.20.14.100",
    "language":"en-US,en;q=0.5",
    "software":"Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:50.0) Gecko/20100101 Firefox/50.0"
}
```

