## This is cloud run sample application

Run this using below commands

gcloud builds submit --tag gcr.io/test-321421/firstcoludrun
gcloud run deploy --image gcr.io/test-321421/firstcoludrun

