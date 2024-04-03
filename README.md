<br/>
<p align="center">
  <a href="https://github.com/WhatsOnDev/developer-documentation">
    <img src="https://whatson.guide/wp-content/uploads/2023/08/Logo-Red-01.png" alt="Logo">
  </a>

  <h3 align="center">ReadME About the Developer Documentation</h3>

  <p align="center">
    The What's On Guide API provides access to information about posts related to specific categories. By using this REST API, developers can retrieve data such as events, articles, or news related to a particular category.
    <br/>
    <br/>
    .
    <a href="https://github.com/WhatsOnDev/developer-documentation/issues">Request Feature</a>
  </p>
</p>


## Table Of Contents

* [About the Project](#about-the-project)
* [Getting Started](#getting-started)
* [License](#license)
* [Authors](#authors)
* [Acknowledgements](#acknowledgements)

## About The Project


The What's On Guide API provides access to information about posts related to specific categories. By using this REST API, developers can retrieve data such as events, articles, or news related to a particular category.


## Getting Started

To get started with the Developer Documentation, follow these steps:

1. Base URL:
  #### https://whatson.guide/wp-json/wp/v2/posts
  ###Endpoints:

2. Retrieve Posts by Category:
  ### Endpoint: /wp-json/wp/v2/posts
  ### Method: GET
  ### Parameters:
    #### categories: (Required) ID of the category for which posts are to be retrieved.
  ### Example Request:
    #### GET https://whatson.guide/wp-json/wp/v2/posts?categories=18172
  ### Example Response:
    [
      {
        "id": 123,
        "title": {
          "rendered": "Sample Post Title"
        },
        "content": {
          "rendered": "Sample Post Content"
        },
        // Other relevant fields...
      },
      // Additional posts...
    ]



3. Authentication:
The API does not require authentication for accessing public data.

4. Rate Limits:
There are no specified rate limits for accessing the API. However, developers are encouraged to use the API responsibly and avoid making an excessive number of requests.

5. Error Handling:
The API follows standard HTTP status codes for indicating the success or failure of a request. Common error codes include:
  ### 200 OK: The request was successful.
  ### 400 Bad Request: The request was invalid or malformed.
  ### 404 Not Found: The requested resource does not exist.
  ### 500 Internal Server Error: An unexpected error occurred on the server.

6. Additional Notes:
  #### The response data is provided in JSON format.
  #### Developers should ensure they have proper error handling mechanisms in place to handle potential issues with API requests.
  #### For any further inquiries or issues regarding the API, developers can contact the #### What's On Guide support team at support@whatson.guide.

7. Terms of Use:
  #### Usage of the API is subject to the terms and conditions outlined by What's On Guide.
  #### Developers should review and comply with the API usage policy to avoid any potential violations.

8. Contribute:
If you find any issues or have suggestions for improvements, please create a new issue or pull request in the GitHub repository.

## License

Distributed under the MIT License. See [LICENSE](https://github.com/WhatsOnDev/developer-documentation/blob/main/LICENSE.md) for more information.

## Authors

* **whatsondev** - *whatsondev is a 360 Digital Solution Agency* - [whatsondev](https://github.com/whatsondev) - *The Brothers Mobile project was primarily developed and maintained by Whatsondev. *
* This project is proprietary software and all rights are reserved by WhatsOn.

## Copyright Notice
Copyright © 2024 WhatsOn . All rights reserved.

## Contact
For any inquiries or requests regarding this project, please contact whatsondev@whatson.agency


