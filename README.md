# vue-devtools
vue-devtools of Chrome
1、github下载地址：https://github.com/vuejs/vue-devtools
2、解压文件

3、进入文件 npm install 
4、然后打包 npm run build
5、找到vue-devtools-master\shells\chrome下的manifest.json文件，将"persistant"的值改为true；原因看http://blog.csdn.net/lecepin/article/details/70172868
6、打开Chrome浏览器的拓展程序，选择开发者模式，加载已解压的文件

7、文件选择vue-devtools-master\shells下的Chrome文件夹

8、选择启用vue devtools，然后重启Chrome浏览器就行了
9、最后保留Chrome文件夹里的就行
