# Web Services [](id=web-services)

It's important for apps on different machines to communicate. To enable this, an
app can expose APIs so remote components (other apps or devices) can access the
app's features. For example, one service could have a client app presenting
information to users, a server app processing data in B2B setting, and an IoT
device requesting data to do its work. Exposing web APIs lets external
applications or devices communicate with yours. 

Because @product@ contains so many apps and features, it's prudent for Liferay
to let developers access those apps and features from external apps and devices
by exposing their APIs. Additionally, Liferay's development platform makes it
easy to extend them and create new ones. 

There are two different approaches for clients to connect to @product@'s web 
APIs: 

-   **Hypermedia REST APIs:** These services are designed and built in an
    opinionated way, and thus decoupled from the internal model. They follow
    well-known industry standards and allow evolution of the APIs without
    breaking clients. This is the modern, preferred way to work with web
    services in @product@. Hypermedia REST APIs are available starting with
    Liferay DXP 7.1 Fix Pack 1 and Liferay Portal CE 7.1 GA2. 

-   **Plain Web/REST Services:** This is the old way to build and consume web 
    services in @product@, but is still supported. For example, you can use 
    JAX-RS, JAX-WS, or 
    [Service Builder](/develop/tutorials/-/knowledge_base/7-1/service-builder-web-services) 
    to implement plain REST or SOAP web services. 

The tutorials that follow show you how to consume and create web services in 
@product@, beginning with hypermedia REST APIs. 
