## Low Code Starter Pack

### This is a bundle of open-source low code software that are configured together using Docker

- The highlights are the configuration between Tooljet and NocoDB which can access the same Postgres database, NocoDB is used here as a no-code backend and ToolJet is the web frontend builder that can use either the Postgres database directly or NocoDB Swagger API as a datasource and build interfaces that perform CRUD operations or transform and display the database content. 

- Usage documentation can be found at NocoDB and ToolJet. Using the NocoDB Swagger API requires creating a token and configuring a custom header on ToolJet side that uses it to authenticate with the API.

