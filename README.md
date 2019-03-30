# fabric-dapp-basis
构建fabric应用所需的底层基础环境
pull_images.sh文件作用：一键下载fabric环境所需要的docker镜像
使用方法：在终端中输入  ./pull_images.sh（下载镜像速度很慢的话，使用阿里云docker镜像加速，自行百度使用）

artifacts和crypto-config两个目录是组织结构

在终端中输入docker-compose up就可以启动fabric网络了
想要停止网络输入docker-compose down
