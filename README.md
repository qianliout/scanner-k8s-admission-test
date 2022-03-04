# scanner-k8s-admission-test

用于测试k8s admisstion controller

## usage

- build image
./build.sh build 一个镜像,然后push到仓库

- deploy
修改deployment.yaml里面为刚才创建的镜像
自己创建一个namespace，然后 ./deploy.sh 进行部署，最后看看是否被拦截掉。

