# Accommodation Finder
	A webapp to find acommodation among the company employees. It is built in maven, Spring boot.

## Documentation
	* This project has an `apiary` documentation. You can check [here](docs.accommodationfinder.apiary.io)
	* The Er diagram of the Database.
	* ![ER Diagram](https://raw.githubusercontent.com/kchetan/accom-finder/master/documentation_files/accommodation_erdiagram.png)

## Installation and Running
	This application is packaged as a `war`.
	* Fill in your database details and other credentials in application.properties
	*  To create a JAR
			`mvn clean generate-sources package`
	* To start application
		- Using jar 
			`java -jar target/car-pool-0.0.1-SNAPSHOT.jar`
		- Without jar
			`mvn spring-boot:run`
	
### Dependencies
	The following should be installed in your machine to run the project.
	* Java 8
	* Maven
	* Msql
