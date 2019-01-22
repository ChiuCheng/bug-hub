```
spring.datasource.test-while-idle=true
spring.datasource.time-between-eviction-runs-millis=3600000
spring.datasource.validation-query=SELECT 1
```
一定不要忘记加上最后的
```
spring.datasource.validation-query=SELECT 1
```
否则不起作用
