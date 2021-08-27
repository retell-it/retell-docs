Azure Deployment
Technologies:
- Azure Kubernetes Service
- Azure Database
- Azure Storage
- Kubernetes
- Docker 

Azure Cluster Size
- 

Connector Development
Two types of connectors: Sources and Destination. A connector takes the form of a Docker image

Connector Development Kit (CDK)
- Python >= 3.7
- Docker
- NodeJS

1. Create the Source: using a code generator which bootstrap the scaffolding for a new connector
2. Install Dependencies: initial python environment
3. Define Inputs: declares the inputs it needs to read data from the underlying data source. This can be done by creating a .json file.
4. Connection Checking: verifies that the input configuration 
5. Declare the Schema
6. Read Data: contains built-in functions or helpers for authentication, pagination, handling rate limiting or transient errors
7. Build Connector: using docker image
8. Test Connector
