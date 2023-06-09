
# Elasticsearch and Spring Boot Search Engine

This project is a simple search engine implemented using Elasticsearch and Spring Boot. It provides an API endpoint to perform searches on a collection of products.

## Prerequisites
Before running this project, ensure that the following prerequisites are met:

 - Java Development Kit (JDK) 8 or above is installed. 
 - Elasticsearch is installed and running on the default port (9200).

## Getting Started
To run the search engine, follow these steps:

 - Clone the repository or download the source code. 
 - Open the project in your preferred IDE. 
 - Configure Elasticsearch:
       - Open the application.properties file located in src/main/resources.
       - Update the property spring.elasticsearch.rest.uris with the appropriate Elasticsearch URI, such as http://localhost:9200
 - Build the project using Maven or your IDE's build feature.
 - Run the application using the main method in the SearchEngineApplication class.
 - The application should start running on the configured port (default is 8080).
 - Use an API testing tool (e.g., cURL, Postman) or a web browser to access the search endpoint:Endpoint: http://localhost:8080/search?query=<your-query>Replace <your-query> with the desired search query.

**API Endpoint**
 Search Products

 - URL: /search
 - Method: GET
 - Query Parameter:
**query** (required): The search query to find matching products based on their name or description.


Query Parameter:
query (required): The search query to find matching products based on their name or description.
The API will return a JSON response containing the list of products that match the search query.

