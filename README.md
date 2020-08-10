# springboot-demo-jpa-mysql
springboot-demo-jpa-mysql
1.项目是通过maven方式构建的   
2.项目启动类  
SpringbootDemoJpaMysqlApplication.java  
3.项目请求地址查看类   
MainController.java   
http://localhost:8080/demo/all  
加载表中所有数据  
http://localhost:8080/demo/add  
默认是post，为了方便试验，可以改为get  
4.application.properties  
注意数据源url的配置，高版本的mysql需要配置serverTimezone，否则无法正常加载数据源  
HHH000342: Could not obtain connection to query metadata : The server time zone value 'EDT' is unrecognized  
