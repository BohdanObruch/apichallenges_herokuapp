# Project Overview

This project contains a Postman collection and an environment configuration for API testing endpoints of [https://apichallenges.herokuapp.com/](https://apichallenges.herokuapp.com/).

## Files

- `Challenges.postman_collection.json`: This file contains a collection of API requests that can be imported into Postman. It includes various endpoints and methods to test the functionality of the API.
- `Env for Challenges.postman_environment.json`: This file provides the environment configuration for the Postman collection. It includes variables such as base URLs, authentication tokens, and other necessary parameters to run the API requests in the collection.

## Usage

1. **Import the Collection**:
   - Open Postman.
   - Click on the `File->Import` button.
   - Select the `Challenges.postman_collection.json` file to import the collection of API requests.

2. **Import the Environment**:
   - In Postman, go to the `Environments` tab.
   - Click on the `File->Import` button.
   - Select the `Env for Challenges.postman_environment.json` file to import the environment configuration.

3. **Set the Environment**:
   - After importing, select the imported environment from the environment dropdown in the top-right corner of Postman.

4. **Run the Requests**:
   - With the environment set, you can now run the requests in the collection. The environment variables will be automatically applied to the requests.
