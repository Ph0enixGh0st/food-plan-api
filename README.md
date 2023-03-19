# Recipe API.
DRF based recipe API that allows to create, modify, and filter recipes and ingredients.

## How to install
Using GitHub CLI:
```bash
gh repo clone Ph0enixGh0st/food-plan-api
```

Or download and unpack ZIP file from GIT Hub repository: https://github.com/Ph0enixGh0st/food-plan-api.git

# Prerequisites
First create .env file in root directory with the following keys and values:

```
DB_NAME=dbname
DB_USER=rootuser
DB_PASS=changeme
DJANGO_SECRET_KEY=changeme
DJANGO_ALLOWED_HOSTS=127.0.0.1
```

Python3 and Docker should be already installed.
Please specify your Docker username and token in GitHub Secrets.
Then use the following command to run the Docker container:
```
docker-compose up
```

## Deployed API is available [here](http://ec2-18-210-17-23.compute-1.amazonaws.com/api/docs)

<img width="1463" alt="image" src="https://user-images.githubusercontent.com/108229516/226186944-4b2af4cf-356e-4144-93b4-a916d2dbf99e.png">
