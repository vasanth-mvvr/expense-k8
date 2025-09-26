# **My sql is created on customized namespace**
```
kubectl get pods -n expense
```
Note : -n expense which is refering the namespace expense not the default namespace. The namespace is used for isolation.
* To see how much resource space allocated.
```
kubectl top pod
```

* To provide traffic in application for pods autoscaling we can test it using apache bench
```
yum install httpd-tools -y
```
* For checking
```
ab -n 50000 -c 500 "url"
```
Note: -c 500 entries at a time.