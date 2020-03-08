# Bitebody Meal Planner Microservice
Team Late's back-end meal planner microservice for bitebody.xyz created via python utilizing AWS Lambda. 

## Deployment

1. Zip this entire repository.
2. Upload zip file to AWS Lambda - mealplanner

## Endpoint

```
https://2o8jsg6z03.execute-api.us-west-1.amazonaws.com/default/mealplanner
```

## Sample JSON

```
{
"request": {
	"diet-type": "Vegan",
	"calories": "2500"
	}
}
```

## Environment Variables

API_USER_KEY
API_USER_ID
API_USER_KEY_BACKUP
API_USER_ID_BACKUP