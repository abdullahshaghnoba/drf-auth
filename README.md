# Project: Cars_App

## Author: Abdullah Shaghnoba

---

### How to initialize:
#### tests: 
- access token route: 'api/token/'
you use this route to get access token for the first time and then use the access token in the request body to get the access permission.
- refresh token route: 'api/token/refresh/'
use this route to get access token after it gets expired and then use the access token in the request body to get the access permission
- 'api/v1/carsApp/': use this route for anny CRUD operations


### how to run the server
#### server: docker compose up 
### how to install requirements
#### pip install -r requirements.txt