# k8s-mirror-dockerfile
这个仓库存放的是搭建 “kubernetes 集群v1.11.2版本” 所需的核心组件的docker镜像的dockerfile；

dockerfile是用来给docker仓库进行“自动构建的。”

因为众所周知的原因，国内用户无法直接访问gcr.io来下载这些镜像，所以只能通过dockerhub或者阿里云容器镜像服务的 “自动构建” 来完成曲线下载的目的了！
