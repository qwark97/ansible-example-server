# install credit card app

* install git
* pobieramy repo gitem
* potrzeban java co najmniej 8
* os packages 
	* java-1.8.0-jdk
	* maven
	* git
* potrzeba maven
* tworzymy jar
	* mvn package
	* target/credit-catd-1.0.jar
* mv target/costam.jar /opt/credit-card-app/costam.jar

* dedykowany user
	* add user thief
* test czy dziala java -jar /opt/credit....
   // nie ma potrzeeby
* konfiguracja systemd
* systemctl start creditcard

* curl mojeip:8080/api/cards
