# GitHub Repositories Search API

This project implements a GitHub Repositories Search API, allowing users to search for GitHub repositories.

## Overview

This API is built using JavaScript and relies on the following main components:

- **Swagger UI**: Swagger UI is used for interactive documentation and testing of the API. It provides a user-friendly interface to explore the available endpoints and make requests.

- **itty-router-openapi**: This library helps create a router for your API based on the OpenAPI Specification. It simplifies the process of defining routes and handling requests.

## API Documentation

You can explore and interact with the API using Swagger UI. Access the documentation by visiting the following URL:

[Swagger UI Documentation](https://swagger.io/docs/)

## Usage

To use this API, you can send GET requests to the `/search` endpoint. Here's an example of how to use it:

```javascript
import { GetSearch } from './search.js';

// ...

router.get('/search', GetSearch);
```

The `GetSearch` function handles the logic for searching GitHub repositories.

**For more details on the API's endpoints and request/response formats, please refer to the Swagger UI documentation.**

## License

This project is licensed under the [MIT License](LICENSE).
