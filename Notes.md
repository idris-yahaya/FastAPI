# Fast API Project Doc

## Notes

### Virtual Environment

- Setup
    - py -3.9 -m venv venv
- Activate
    - .\venv\Scripts\activate
- Deactivate
    - deactivate
-   Installations
    - pip install fastapi

### API's
- Set of rules and protocols that contract between two software entities, defining how they can interact. It specifies the types of requests that can be made, how to make them, the data formats to use, and the conventions to follow.

- Key Terminology
  - **Endpoint**: URL where an API function or resource can be accessed (e.g., `https://api.example.com/users`).
  - **Request**: Message sent by a client to an API, containing:
    - **Method**: Action to be performed (e.g., GET, POST, PUT, DELETE).
    - **Headers**: Metadata about the request (e.g., content type, authentication tokens).
    - **Body**: Data (usually in JSON format) sent to the API (mainly used in POST and PUT requests).
  - **Response**: Message sent back by the API to the client, containing:
    - **Status Code**: Indicates the result of the request (e.g., 1xx - Informational, 2xx - Success, 3xx - Redirection, 4xx - Client Error, 5xx - Server Error).
    - **Headers**: Metadata about the response.
    - **Body**: Data returned by the API.
  - **Authentication**: Process ensuring the client has permission to access the API.
    - Common methods include API keys, OAuth tokens, and JWT (JSON Web Tokens).

- Types of APIs:
  - **REST (Representational State Transfer)**: Uses standard HTTP methods, designed to be stateless and scalable. Each URL represents a resource, with operations (GET, POST, PUT, DELETE) mirroring CRUD actions.
  - **SOAP (Simple Object Access Protocol)**: Protocol for structured information exchange in web services, utilizing XML with strict standards and error handling.
  - **GraphQL**: Allows clients to request specific data, using a single endpoint instead of multiple for different resources.
  - **Webhooks**: APIs delivering real-time data to other applications; triggers payloads to specified URLs upon event occurrence.


### FastAPI
- [FastAPI Docs](https://fastapi.tiangolo.com/)
- [FastAPI Tutorial](https://www.youtube.com/watch?v=0sOvCWFmrtA)
- [text](https://www.fastapitutorial.com/)



### Miscellaneous
- '@' Decorators
  - Allow you to modify the behavior of the function below it
- 'async' and 'await'
  - Define asynchronous functions which are functions that can run concurrently with other code

## New Knowledge & Tools
- Virtual Environments
- FastAPI
- Postman
- Swagger

## Research
- SDLC, Methodologies
- Containers: Docker
- Gitlab
- CI/CD
- Cloud Providers: AWS