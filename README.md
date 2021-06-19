# K8s-mongo
Configuration files to deploy an instance of mongo-db and mongo express to an AKS cluster.

## To deploy:
* apply secrets --> ````kubectl apply -f mongodb-secret.yaml````

* apply database deployment --> ````kubectl apply -f mongodb-deployement.yaml````
* apply configmap --> ````kubectl apply -f mongo-configmap.yaml````
* apply mongo-express deployment --> ````kubectl apply -f mongo-express-deployement````
