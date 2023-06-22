# Crowdstrike-Discover-Application
Sample Crowdstrike Application Script to filter and pull Application Data
This python script has 3 stages
1. Authenticate via auth0 and gets the token
2. Gets the application ids from the API endpoint: "/discover/queries/applications/v1"
3. Uses the application ids to get details from the API endpoint: "/discover/entities/applications/v1?ids="
