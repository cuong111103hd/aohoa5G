# Ảo hóa 5G Viettel 2024

Clone file từ git hub về:
```
git clone https://github.com/cuong111103hd/aohoa5G
```
## Challenge lab 1:
Vào thư mục chưa challenge lab 1:

```
cd aohoa5G/B1
```
Apply deployment va service:
```
kubectl apply -f nginx-deployment.yaml
kubectl apply -f nginx-service.yaml
```
Run default website nginx:
```
minikube service nginx-service 
```
## Challenge lab 2:

Vào thư mục chưa challenge lab 2:
```
cd aohoa5G/B2
```
Apply deplyment and service:
```
kubectl apply -f static-web-deployment.yaml
kubectl apply -f static-web-service.yaml
```
Run web
```
minikube service static-web-service
```
## Challenge lab 3:

Vào thư mục chứa challenge lab 3:
```
cd aohoa5G/B3
```
Apply deployment and service cho web1 and web2
```
kubectl apply -f static-web-deployment.yaml
kubectl apply -f static-web-service.yaml
kubectl apply -f static-web2-deployment.yaml
kubectl apply -f static-web2-service.yaml
```
Appy deployment, service and config cho proxy
```
kubectl apply -f nginx-proxy-config.yaml
kubectl apply -f nginx-proxy-deployment.yaml
kubectl apply -f nginx-proxy-service.yaml
```
Run web
```
minikube service web1 web2
```
