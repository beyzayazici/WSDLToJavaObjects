# Convert WSDL to Java Objects
This project built using Java and the apache cxf plugin:
* Maven as build automation tool
* Apache cxf plugin used converting from wsdl to java object.
* Your dependeny requirements could be change according to your wsdl. In this case, you need to add your dependencies to the dependency tag in pom.xml.

 # Build Project
 * Adding your wsdl file under to resources folder.
 * After adding your wsdl write the name of your wsdl in pom.xml wsdl tag area. 
 * Build application using the following maven command.
 - mvn clean install
 * You can find your java objects under target/generated-sources/cxf. You can change this folder in pom.xml sourceRoot area.