参考：

https://blog.csdn.net/lusyoe/article/details/79673058
https://www.cnblogs.com/learn-ops/p/10055573.html
https://www.jianshu.com/p/adf2aebdc381
https://www.cnblogs.com/neutronman/p/8047547.html

常用命令：

yum install - y etcd kubernetes
systemctl start etcd docker kube-apiserver kube-controller-manager kube-scheduler kubelet kube-proxy
kubectl create -f mysql-rc.yaml等
kubectl delete -f mysql-rc.yaml等
kubectl get rc 或 pods 或者 svc
kubectl describe pod podName