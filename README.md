# Database setup
    docker run --name postgresdb -e POSTGRES_USER=admin -e POSTGRES_PASSWORD=123qwe -p 5432:5432 -d postgres
    
# Minikube deployment
    kubectl apply -f kube

Rest api was dockerized and deployed with kubernetes. Meanwhile, environment variables were put into configmap and secret services so the system was centralized.
