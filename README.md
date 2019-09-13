# rook-ceph
rook-ceph 存储管理工具

### 安装步骤：

#### 1.使用helm
https://github.com/rook/rook/tree/master/cluster/charts/rook-ceph

helm install --namespace rook-ceph --name rook-ceph rook-ceph的目录

#### 2. 创建集群

kubectl apply -f cluster.yaml

#### 3.创建存储类StorageClass

kubectl apply -f srotageclass.yaml
