# Files to accompany the How deploy Prometheus on Kubernetes video

Find the video at https://www.youtube.com/watch?v=V4ApOm37XCU

TLDR

Execute following commands to deploy Prometheus 

1. kubectl apply -f monitoring-namespace.yaml
2. kubectl apply -f prometheus-config.yaml
3. kubectl apply -f prometheus-roles.yml
4. kubectl apply -f prometheus-deployment.yaml
5. kubectl apply -f prometheus-nodeservice.yaml


Currently the prometheus-config is scraping the set of spaceinvaders metrics at 8080.
