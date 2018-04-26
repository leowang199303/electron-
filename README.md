# electron-
超柜打包教程和结构图


一、安装electron


使用淘宝镜像安装

淘宝镜像:npm install -g cnpm --registry=https://registry.npm.taobao.org


指令:  cnpm install -g electron





安装好了之后，是一个压缩包,解压










二、新建 一个文件夹，名字随便起，就是配置工程文件夹，例如 Demo

在工程文件夹Demo中 
①、新建文件 main.js(配置electron主要文件)  可以直接用我配置好的，这里主要是配置地址作用



此时把工程文件放入Demo文件夹，因为我们在loadURL中配置了路径，一一对应上.




②、npm install 生成的package.json，里面加入打包配置（目前可直接用我配置好的，这里主要是配置打包指令的）





③、main.js  和 package.json 配置好了之后,然后安装打包插件

指令: npm install --save-dev electron-packager

安装完成之后,此时DEMO中目录结构应该如下:





Main.js  主要配置文件  package.json  依赖文件  node-modules  依赖库   superCounter 工程文件夹


npm
④、打包

使用指令 : npm run-script packager 


⑤、打包完成之后 结构




安装好了之后，打开对应文件夹，找到.exe程序 打开即可
