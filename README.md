# Open API scheme for Semrush AppCenter server API

This API allows seamless integration with 
[Semrush AppCenter](https://www.semrush.com/apps/docs/), 
providing developers with access to essential functionalities.

The AppCenter provides information about user purchases and sessions 
through [the browser API](https://www.semrush.com/apps/docs/js-sdk-reference/overview). 
However, there are situations where developers need to implement 
certain actions on the server-side. For these purposes, we have created 
[Server to Server API](https://www.semrush.com/apps/docs/server-to-server-api/overview).

The functionality of this API can be divided into three blocks:

* Mechanism for providing access keys ([link](https://www.semrush.com/apps/docs/server-to-server-api/bearer-token))
* Retrieving user information ([link](https://www.semrush.com/apps/docs/server-to-server-api/viewer-status))
* Managing email mailings ([link](https://www.semrush.com/apps/docs/server-to-server-api/notifications))

All methods from these blocks are described in the schema.

## OpenAPI Schema

To facilitate a standardized and comprehensive understanding of our API, 
we provide the OpenAPI schema. The OpenAPI schema serves as a blueprint 
for the API, defining endpoints, data formats, authentication methods, 
and more. This schema is crucial for developers as it ensures clarity, 
consistency, and ease of integration.

### [OpenAPI Schema](https://www.openapis.org/)

## Getting Started

To begin integrating with the Semrush AppCenter API, refer to the 
[OpenAPI Schema Specification](openapi_spec.yaml). 
This documentation provides detailed insights into the API's structure, 
endpoints, request/response formats, and authentication methods.

You can download [this file](swagger_ui.html) and try it in your browser 
locally.

We encourage developers to leverage the OpenAPI schema as a valuable 
resource throughout the development process. If you have any questions 
or need assistance, feel free to reach out to our support team.

Happy coding!
