# Spring cloud - Hystrix, Turbine & Hystrix Dashboard.
### Spring cloud Netflix components
~~~
  1. Hystrix circuit breaker
  2. Turbine
  3. Hystrix Dashboard
~~~  
### Please check my LinkedIn Article for more explanations.

## Project Build
### Pre-requisites
1.  Java8
### Build Steps:
1. clone the project from the gitHub: 
2. From Project directory, run - `./gradlew clean build`
3. Start the spring boot app, run - `./gradlew :<moduleName>:bootRun`. For example, `./gradlew :registry:bootRun`

##Access the below REST Endpoints.
~~~
http://localhost:8080/customer/order/1
http://localhost:8080/customer/product/recommendation/1
~~~  

##Hystrix Dashboard URL 
~~~
DashBoard URL: http://localhost:8084/hystrix
Provide the Hystrix URL : http://localhost:8081/actuator/hystrix.stream
Provide the Turbine Stream URL: http://localhost:8084/turbine.stream?cluster=CUSTOMER
~~~ 
