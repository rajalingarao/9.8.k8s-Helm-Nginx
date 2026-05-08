$git clone https://github.com/Lingaiahthammisetti/9.8.k8s-Helm-Nginx.git

$cd 9.8.k8s-Helm-Nginx

$ls -l
```
helm install nginx .
```
```
kubectl get pods -n expense
```
```
helm upgrade nginx .
```
```
helm status nginx
```
```
helm list
```
```
helm history nginx
```
```
helm uninstall nginx
```

cd /usr/share/nginx/html/
ls -l

rm -rf /usr/share/nginx/html/index.html
echo "<h1>This is nginx server using helm chart. </h1>" > /usr/share/nginx/html/index.html

http://a085fb8e0ad784ea1ab9c21fe27061fd-1774238623.us-east-1.elb.amazonaws.com

# Comment below lines for nginx server.
  
  #location /api/ { 
  #    proxy_pass http://backend:8080/;
  #}
