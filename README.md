# Red5-bwcheck
this is  Red5 bandwidth check for red5-server-1.0.6
# how run
1 用flex builder 3 打开flex-client下的bwcheck，然后找到你项目bwcheck,然后右键bwcheck.mxml。运行
2 启动你的red5服务器。
3 如果再eclipse没有安装惹到插件。你需要用maven编译源码后，拷贝到red5服务器上的webapps目录下，然后重新启动red5服务器
4 找到server下的bwcheck。这是带宽检测的，服务器端程序，需要运行再red5服务器上。
5 cd ./server/bwcheck
6 mvn clean install
7 打包成功后 把bwcheck发布到red5上

