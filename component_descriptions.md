# Reusable X-road components

## Table of Contents
* [X-Road Portal MISP2](#x-road-portal-misp2)
* [X-Road WSDL validator](#x-road-wsdl-validator)
* [X-Road Personal Data Monitor](#x-road-personal-data-monitor)
* [X-Road Generator (X-tee .NET)](#x-road-generator-x-road-net)
* [J-road](#j-road)
* [REST-Gateway](#rest-gateway)
* [Publish-Subscribe](#publish-subscribe)
* [XRd4J](#xrd4j)
* [SAP PI X-Road Adapter](#sap-pi-x-road-adapter)
* [XRDv4WSDLConverter](#xrdv4wsdlconverter)


##X-Road Portal MISP2

**Component type**: 
Functional component.

**Description**: 
MISP2 is a universal portal application that allows organizations to execute X-Road services opened to them without having to develop their own X-road applications.

**Developer**: 
RIA.

**Download location**: 
http://x-road.ee/misp2/packages/dists/

**Documentation**: 
http://x-road.ee/misp2/docs/ (ENG + EST)

**Currency**: 
Current, last updated 30.12.2015.

**Licence**: 
Unknown.

**Technology used**: 
Unknown.

**Component requirements**: 
Ubuntu Server 10.04 Long-Term Support (LTS), 64-bit version; Java 6, PostgreSQL 8.4.

##X-Road WSDL validator

**Component type**: 
Developer tool.

**Description**: 
WSDL validator has been created in order to check the X-Road services. The plug-in programme validates and feedbacks the provided WSDLs. Based on the received feedback, the institution may improve its X-Road service descriptions.

**Developer**: 
RIA. (Developed by Aktors OÜ).

**Download location**: 
http://x-road.ee/valid/

**Documentation**: 
User guide: http://x-road.ee/valid/X-road_WSDLvalidator_user_guide.pdf 

**Currency**: 
Current, last modified 22.01.2016.

**Licence**: 
Unknown.

**Technology used**: 
Unknown.

**Component requirements**: 
Linux (Debian), Windows, Java JRE 6+.

##X-Road Personal Data Monitor

**Component type**: 
Functional component.

**Description**: 
Personal Data Monitor, **Andmejälgija** in Estonian, is a set of 4 microservice-style applications that, when combined with each other and attached to X-Road can offer the citizen the comprehensive view of how his or her personal data has been used by the government.

**Developer**: 
RIK. (Developed by Degeetia).

**Download location**: 
https://github.com/e-gov/AJ/ 

**Documentation**: 
http://e-gov.github.io/AJ/Presentation/ 

**Currency**: 
Still in development.

**Licence**: 
Unknown.

**Technology used**: 
Unknown.

**Component requirements**: 
Unknown.

##X-Road Generator (X-Road .NET)

**Component type**: 
Developer tool.

**Description**: 
X-Road generator created by the Centre of Registers and Information Systems is meant for software developers who work on information systems that use X-Road services. The solution has been developed to simplify interfacing with X-Road projects on .NET platform and is available to everyone free of charge.

X-Road generator allows to generate a list of data objects used on the basis of a list of services (wsdl) offered by any information system providing X-Road services of the public or private sector, thus making the use of those services notably easier as the developer does not have to try to make sense of the list of services and all the information needed in his work is in a readily usable form.

**Developer**: 
RIK.

**Download location**: 
http://xtee.codeplex.com/ 

**Documentation**: 
http://www.rik.ee/et/muud-teenused/x-tee-generaator 
http://xtee.codeplex.com/documentation 

**Currency**: 
Last modified 21.04.2015.

**Licence**: 
Apache License 2.0
http://xtee.codeplex.com/license 

**Technology used**: 
.NET.

**Component requirements**: 
Unknown.

##J-road

**Component type**: 
Developer tool; also adapter?

**Description**: 
J-road is a Java library which simplifies the consumption and creation of Estonian X-road services through code generation and protocol implementation.
The library was initially created for internal use in Webmedia Group AS (now known as Nortal AS), where it is used in all projects requiring X-road functionality.
It consists of two parts: the client, which is used for consuming services from databases created by others and the server, which allows you to create your own databases.

**Developer**: 
Nortal.

**Download location**: 
https://github.com/nortal/j-road

**Documentation**: 
http://j-road.googlecode.com/svn/trunk/etc/x-tee-kasutusjuhend.doc (EST), last modified in 2010.

**Currency**: 
Current, last updated 30.03.2016.

**Licence**: 
GNU LESSER GENERAL PUBLIC LICENSE.
https://github.com/nortal/j-road/blob/master/etc/License.txt 

**Technology used**: 
Java.

**Component requirements**: 
X-road version 4 support.

##REST-Gateway

**Component type**: 
Adapter.

**Description**: 
REST Gateway is a component that sits between X-Road security server and a REST service. It translates SOAP messages to REST service requests and vice versa.  It includes the following features:
* Provider Gateway - access REST services (JSON, XML) via WSDL defined X-Road services,
* Consumer Gateway - access WSDL defined X-Road services in a RESTful manner.

**Developer**: 
VRK

**Download location**: 
https://github.com/educloudalliance/xroad-rest-gateway 

**Documentation**: 
https://github.com/educloudalliance/xroad-rest-gateway/wiki 

**Currency**: 
Current.

**Licence**: 
European Union Public Licence V. 1.1
https://github.com/educloudalliance/xroad-rest-gateway/blob/master/LICENSE 

**Technology used**: 
Java.

**Component requirements**: 
Software requirements: Java 6 or later, Tomcat 6 or later. The component implements X-Road v4.0 SOAP profile and it's compatible with X-Road v6.4 and above.
See also: https://github.com/educloudalliance/xroad-rest-gateway/wiki/Requirements

##Publish-Subscribe

**Component type**: 
Developer tool/adapter?

**Description**: 
TODO.

**Developer**: 
Elering.

**Download location**: 
Unknown.

**Documentation**: 
Unknown.

**Currency**: 
In development.

**Licence**: 
Unknown.

**Technology used**: 
Unknown.

**Component requirements**: 
Unknown.

##XRd4J

**Component type**: 
Adapter?

**Description**: 
XRd4J is a Java library for building X-Road v6 Adapter Servers and clients. The library implements X-Road v6 SOAP profile v4.0 and Service Metadata Protocol. The library takes care of serialization and deserialization of SOAP messages: built-in support for standard X-Road SOAP headers, only processing of application specific request and response elements must be implemented.

**Developer**: 
Finnish X-Road Community

**Download location**: 
https://github.com/petkivim/xrd4j

**Documentation**: 
https://github.com/petkivim/xrd4j 

**Currency**: 
Current, last updated 21.03.2016.

**Licence**: 
The MIT License (MIT). https://github.com/petkivim/xrd4j/blob/master/LICENSE 

**Technology used**: 
Java.

**Component requirements**: 
X-road version 6, protocol version 4.0.

##SAP PI X-Road Adapter

**Component type**: 
Adapter.

**Description**: 
X-Road adapter for Estonian Health Insurance Fund SAP PI.

**Developer**: 
Intelsys?

**Download location**: 
Unknown.

**Documentation**: 
Unknown.

**Currency**: 
Unknown.

**Licence**: 
Unknown.

**Technology used**: 
Unknown.

**Component requirements**: 
Unknown.

##XRDv4WSDLConverter 

**Component type**: 
Developer too.

**Description**: 
X-road WSDL Converter converts old version 2 and 3 WSDL files into version 4 WSDL.

**Developer**: 
RMIT

**Download location**: 
https://github.com/alar-saat/XRDv4WSDLConverter 

**Documentation**: 
https://github.com/alar-saat/XRDv4WSDLConverter 

**Currency**: 
Current, last updated 29.03.2016.

**Licence**: 
https://github.com/alar-saat/XRDv4WSDLConverter/blob/master/LICENSE.md 

**Technology used**: 
Java.

**Component requirements**: 
Java SDK 8. Supported X-road protocol versions: 2, 3, 4.
