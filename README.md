# Used Junit test @test
## @DataJpaTest used test JPA respositorys
## @TestMethodOrder(MethodOrderer.OrderAnnotation.class) Annotated with class to maintain the order
## @Order(1) used with method to understand the order 
## @Rollback(value = false) Because it execution is happening in single transaction some test cases will be fail
## To avoid this we used @Rollback annotation here.
![image](https://github.com/shankarthakur/Spring-boot-crud-testing/assets/48851003/a6461130-dd1a-492e-ad91-43ad80f74dc3)
