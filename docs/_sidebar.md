<img src="https://upload.wikimedia.org/wikipedia/commons/2/25/NuGet_project_logo.svg" width="70" height="70"/>

* Olive Core
    * [What is Olive?](README.md)
    * [Getting Started (Console app)](Core/Setup.md)
    * [.NET Extensions](Core/Extensions.md)
    * [Utility classes](Core/Utilities.md)
    * [change log](ChangeLog.md)
    
* Olive Entities
    * [Overview](Entities/Overview.md)
    * [Lifecycle events](Entities/Lifecycle.md)
    * [Ado.NET & Raw data access](Entities/RawDataAccess.md)
    * [Olive ORM](Entities/ORM.md)
       * [Caching](Entities/Cache.md)
    * [Database Api](Entities/Database.md)
       * [IDatabaseQuery](Entities/IDatabaseQuery.md)
    * [Provider model and DI](Entities/DI.md)
    * [Files and Blobs](Entities/Blob.md)
    * [Custom data type](Entities/CustomDataType.md)
    * [Using C# Enums](Entities/CSharpEnumType.md)

* Microservices Architecture
    * [Understanding Microservices](Microservices/UnderstandingMicroservices.md)
    * [Understanding Docker](Microservices/DockerMicroservices.md)
    * [Distributed Data](Microservices/DistributedDataInMicroservices.md)
    * [Microservice Boundaries](Microservices/MicroserviceBoundaries.md)
    * [Intra-service Communication](Microservices/IntraServiceCommunication.md)
    * [Implementing Resilient Apps](Microservices/ImplementingResilientApplications.md)
    * [Development Process for Docker-Based Apps](Microservices/DockerBasedApplications.md)
    * [Security in Microservices](Microservices/SecurityInMicroservices.md)
    * [Loading a typescript service module](Microservices/LoadTypescriptServiceFromController.md)
    * [Use AWS S3 as the temp folder to upload files](Microservices/AwsS3TempBlobStorage.md)
 
* Microservices in Olive
    * [Access Hub: Composite UI](Microservices/Overview.md)  
    * [Environment Setup](Microservices/Setup.md)
        * [Private Nuget Server](Microservices/PrivateNuget.md)
    * [Security (Auth)](Microservices/Security.md)
    * [Urls and Addressing](Microservices/Addressing.md)
    * [Creating a new microservice](Microservices/Create.New.md)
 

* DevOps
    * [Introduction](DevOps/Introduction.md)
    * [DevOps Automation Service](DevOps/Automation-Service.md)
    * [Docker support](DevOps/Docker.md)
    * [Jenkins](DevOps/Jenkins.md)
    * [Jenkinsfile template](DevOps/MSharp-Jenkinsfile.md)
    * [Jenkinsfile server](DevOps/PreparingJenkinsServer.md)
    * [Cluster setup (Kubernetes & AWS)](DevOps/Cluster-setup.md)
    * [Security](DevOps/Security.md)
    * [Service preparation](DevOps/Service-preparation.md)
    * [Serverless deployment](DevOps/Serverless.md)
        
* Sync integration: WebApi
    * [RESTful WebApi](Api/WebApi.md)
    * [ApiClient](Api/ApiClient.md)
    * [Api Proxy](Api/Proxy.md)
    * [Api Versioning](Api/Versioning.md)

* Async integration: EventBus, Queues
    * [EventBus](Api/EventBus.md)
    * [EventBus Commands](Api/EventBusCommands.md)
    * [Data Replication](Api/Replication.md)

* Javascript Fx (MvcJS)
    * [Overview](MvcJS/Overview.md)
    * [Ajax Lifecycle](MvcJS/AjaxLifecycle.md)
    * [Loading custom modules and libraries](MvcJS/Library.md)
    * [Migration to version 2](MvcJS/MigrationAndDI.md)
    
* Plugins
    * [Compression](Services/Compression.md)
    * [Email notifications](Services/Email.md)
    * [SMS notifications](Services/SMS.md)
    * [GeoLocation](Services/GeoLocation.md)
    * [Globalization](Services/Globalization.md)
    * [Data Export](Services/DataExport.md)
    * [Parsing CSV](Services/CSV.md)
    * [PDF generation](Services/PDFgeneration.md)
    * [Push Notifications](Services/PushNotification.md)
    * [Image optimization](Services/Imageoptimization.md)
    * [Website IP Filter](Services/WebsiteIPFilter.md)
    * [AWS integration](Services/Aws.md)
    * [Captcha](Security/Captcha.md)

* Security
    * [Olive Security Overview](Security/Security.md)
    * [Captcha](Security/Captcha.md)
    * [Config](Security/Config.md)
    * [Impersonation](Security/Impersonation.md)
    * [Encryption and Decryption](Security/Encryption%20and%20Decryption.md)
    
* Logging & Audit
    * [Olive Logging Overview](Logging/Logging.md)
    * [Olive Audit](Logging/Audit.md)
    * [NLog integration](Logging/NLog.md)

* Tips & Tricks
    * [Dev Commands](Tips/DevCommands.md)
    * [Database profiling](Tips/ProfileDatabase.md)
     
