# GKE

## git clone https://github.com/GoogleCloudPlatform/nodejs-docs-samples.git


## export PROJECT_ID="$(gcloud config get-value project -q)"

## docker build -t gcr.io/$PROJECT_ID/hello-app:v1 .

## docker images

## gcloud container clusters create hello-cluster --num-nodes=3

## gcloud config set compute/zone us-central1-b

## gcloud container clusters create hello-cluster --num-nodes=3

## gcloud docker -- push gcr.io/${PROJECT_ID}/hello-app:v1

## kubectl run hello-web --image=gcr.io/${PROJECT_ID}/hello-app:v1 --port 8080

## kubectl get pods

## kubectl expose deployment hello-web --type=LoadBalancer --port 8080

## Kubectl get Service 

## kubectl scale deployment hello-web --replicas=3
