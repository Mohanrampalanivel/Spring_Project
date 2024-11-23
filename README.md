# Spring_Project
Ecommerce- Spring CURD operation projects

spring project
1. install java, MySQL
2.spring boot intializr - generate(use java 17th version, 3.3.6)

3.open in vscode and run, we will get failure to execute
	because of mysqcl connection - ...Projects\spring\target\classes\application.properties
		"spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
		spring.datasource.url=jdbc:mysql://localhost:3306/spring //spring is a database created in mysql
		spring.datasource.username=root
		spring.datasource.password=root

		spring.jpa.show-sql=true
		spring.jpa.hibernate.ddl-auto=update"

4. run -executed in localhost8080
