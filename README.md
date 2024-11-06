# Ảo hóa 5G Viettel 2024

Clone file từ git hub về:
```
git clone https://github.com/cuong111103hd/aohoa5G
```
## Challenge lab 1:
```
#Vao thu muc chua challenge lab 1
cd aohoa5G/B1
#Apply deployment va service
kubectl apply -f nginx-deployment.yaml
kubectl apply -f nginx-service.yaml
#Run default website nginx
minikube service nginx-service 
```
## Challenge lab 2:
```
#Vao thu muc chua challenge lab 2
cd aohoa5G/B2
#Apply deplyment and service
kubectl apply -f static-web-deployment.yaml
kubectl apply -f static-web-service.yaml
#Run web
minikube service static-web-service


```
## Challenge lab 3:
```
#Vao thu muc chua challenge lab 3
cd
#Apply deployment and service cho web1 and web2

#Appy deployment, service and config cho proxy


```
