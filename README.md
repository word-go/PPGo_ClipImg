PPGo_CliImg
====
什么东西？What?
----
基于Golang的图片截取工具。可以将底色是白色或者纯色的图片切割出来，并按照自定义尺寸和边距输出。类似另外一个python项目的效果：
https://github.com/george518/CoreImage

有什么价值？
----
1、快速切割图片的核心部分，并自定义尺寸和边距形成新的图片   
2、常用于电商平台的图片批量处理。    
3、含有golang常用的图片包使用方法，可以作为golang图片学习参考使用        

效果展示 （图片显示均为正常尺寸）
----
原图1<br/>
![github](https://github.com/george518/PPGo_CliImg/blob/master/example/images/image.jpg?raw=true "github")
<br/><br/>
处理图1<br/>
![github](https://github.com/george518/PPGo_CliImg/blob/master/example/images/CoreImages/image.jpg?raw=true "github")
原图2<br/>
![github](https://github.com/george518/PPGo_CliImg/blob/master/example/images/png.png?raw=true "github")
<br/><br/>
处理图2<br/>
![github](https://github.com/george518/PPGo_CliImg/blob/master/example/images/CoreImages/png.png?raw=true "github")
<br />
更多切割效果查看example中的例子<br />

安装使用    
----
1、go get github.com/george518/PPGo_CliImg        
2、运行 go build    
使用示例：    
./PPGo_CliImg -f=./example/images/image.jpg -p=center -h=300 -w=200 -m=10    
具体可以使用 ./PPGo_CliImg -h 查看传入参数    

联系我
----
qq:41352963
