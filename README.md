# Description
Your task is to create a REST service with the following endpoints:
`POST /value`
`GET /sum`

POST /value will accept requests with a body containing a JWT token. Find the JWT secret used to sign the tokens in the README.MD in the project repository.
Each token will contain a claim called “value” in its payload. Only valid JWT tokens must be accepted.

GET /sum will return the sum of all “values” accepted so far as JSON:
{
  “sum”: <value>
}

# Fetching initial project skeleton
git clone https://eval.best/demo/a4aa5b34.git

# Deploying your solution
To deploy your solution simply git push.

# Accessing application logs
The logs will be available at: https://eval.best/demo/a4aa5b34/logs
