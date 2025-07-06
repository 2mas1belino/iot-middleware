# SOMIOD: Service Oriented Middleware for Interoperability and Open Data  
**A C# middleware for IoT interoperability with RESTful API, MQTT/HTTP notifications, and hierarchical resource management.**  

## Features  
- **Resource Management**  
  - CRUD operations for Applications, Containers, Data, and Subscriptions  
  - Hierarchical structure (3-level depth: Application → Container → {Data/Subscriptions})  
  - XML data format for all transactions  
- **Notification System**  
  - Event-driven subscriptions (creation/deletion events)  
  - Dual-channel notifications (HTTP POST or MQTT publish)  
- **Database Persistence**  
  - SQL Server storage for all resources and metadata  
  - Automatic unique ID/name generation  

## Technologies  
| Component       | Tech Stack |  
|-----------------|------------|  
| **Backend**     | C# |  
| **API**         | RESTful Web Service |  
| **Messaging**   | MQTTnet library for MQTT support |  
| **Database**    | SQL Server |  
| **Serialization** | XML data format |  

## Project Context
Developed for System Integrations (3rd Year, 1st Semester) at Institute Polythecnic of Leiria (2023/2024).
Team: Tomás Umbelino, Renato Medeiros, Luís Adão, Carlos Franco
