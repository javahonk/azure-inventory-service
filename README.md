### Overview

This service is developed on to use Microsoft Azure

Inventory Service receives a request to update the inventory. It looks for a Feature Flag value in a Config Server and based on the value, the inventory data in the Azure Cosmos DB is updated. 	

Inventory Service will make use of Service Registry (Eureka), Config Server (Git) and Cosmos DB binding features of [Azure Spring Cloud](https://azure.microsoft.com/en-us/services/spring-cloud/).	

