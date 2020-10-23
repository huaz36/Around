# Around
## Introduction
This project aims to provide a geo-based social network web application where users can post message, and media files, and can also find any other user's posts (filtered by Google Vision for human face score > 0.9) nearby in Google Map.

## Technologies
* Frontend: React JS, Ant Design
* Backend: Go, Elasticsearch (database and good for searching geo-locations), GCE (Google Compute Engine), GKE (Google Kubernetes Engine), GCS (Google Cloud Storage, for storing media files), Google Vision API (to provide face detection model)

## Setup
The backend service is deployed in Google Cloud. 
* Restart VM instance in GCE
* SSH to the VM and go run index.go, main.go, user.go, vision.go
* Update the backend IP address in frontend code
* npm start frontend code in local IDE
