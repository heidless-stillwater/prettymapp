

# Build and deploy

Command to build the application. PLease remeber to change the project name and application name
```
# gcloud builds submit --tag gcr.io/<ProjectName>/<AppName>  --project=<ProjectName>

gcloud builds submit --tag gcr.io/h-pfolio/prettymapp  --project=h-pfolio

```

Command to deploy the application
```
gcloud run deploy --image gcr.io/h-pfolio/prettymapp --platform managed  --project=h-pfolio --allow-unauthenticated

```
