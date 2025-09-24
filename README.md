Create Microservice Consumer Service :
  1)Apply Annotation @EnableEurekaClient and @EnableFeignClients at the main class
  2)Modify application.properties file
  3)Create Model class as Book.java
  4)Create an interface as BookRestConsumer.java
  5)Create a RestController as StudentRestController.java

How to test FeignClient Enabled Microservice?
http://localhost:9100/student/data
http://localhost:9100/student/allBooks
http://localhost:9100/student/getOneBook/501
http://localhost:9100/student/entityData
