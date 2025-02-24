There are various ways to setup. 
1) You can use with MSQL 
2) You can use with SQLLite

## About Ghost
After installation goto : http://localhost:8080/ghost 
Enter site title, create a username and password etc

### API
To get an API key 
1) Navigate to "Settings" → "Integrations"
2) Create a New Integration
3) Click "Add custom integration".
4) Adding details 
- Give a name 
- Give the admin api endpoint 
- Content API - (Used for getting the content)
- Admin API (Staff API Key) - (Used for admin related work)

Note : Restart the docker containers to make sure that the authentication is reflected. 

