<!-- loio1f066330e8314324bf3ebe3b6adc21b2 -->

# Configure Adapter in Communication Channels

You should configure the adapters assigned to communication channels before deploying the integration flow.

The following adapter types are available:

**Adapter**


<table>
<tr>
<th valign="top">

Feature



</th>
<th valign="top">

Description



</th>
</tr>
<tr>
<td valign="top">

*AmazonWebServices* 

Sender adapter



</td>
<td valign="top">

Connects SAP Integration Suite to Amazon Web Services.

The adapter supports the following protocols:

-   S3: Simple Cloud Storage

-   SQS: Simple Queue Service


See: [AmazonWebServices Sender Adapter](amazonwebservices-sender-adapter-16772e3.md)



</td>
</tr>
<tr>
<td valign="top">

*AmazonWebServices* 

Receiver adapter



</td>
<td valign="top">

Connects SAP Integration Suite to Amazon Web Services.

The adapter supports the following protocols:

-   S3: Simple Cloud Storage

-   SQS: Simple Queue Service

-   SNS: Simple Notification Service

-   SWF: Simple Workflow Service


See: [AmazonWebServices Receiver Adapter](amazonwebservices-receiver-adapter-bc7d1aa.md)



</td>
</tr>
<tr>
<td valign="top">

*AMQP*

Sender adapter



</td>
<td valign="top">

Enables SAP Integration Suite to consume messages from queues or topic subscriptions in an external messaging system.

Supported message protocol: AMQP \(Advanced Message Queuing Protocol\) 1.0

Supported transport protocols: TCP, WebSocket

See: [Configure the AMQP Sender Adapter](configure-the-amqp-sender-adapter-99ce674.md)



</td>
</tr>
<tr>
<td valign="top">

*AMQP*

Receiver adapter



</td>
<td valign="top">

Enables SAP Integration Suite to send messages to queues or topics in an external messaging system.

Supported message protocol: AMQP \(Advanced Message Queuing Protocol\) 1.0

Supported transport protocols: TCP, WebSocket

See: [Configure the AMQP Receiver Adapter](configure-the-amqp-receiver-adapter-d5660c1.md)



</td>
</tr>
<tr>
<td valign="top">

*AMQP for SAP Event Mesh*

Sender adapter



</td>
<td valign="top">

Enables SAP Integration Suite to consume messages from queues or topic subscriptions in SAP Event Mesh.

Supported message protocol: AMQP \(Advanced Message Queuing Protocol\) 1.0

Supported transport protocol: WebSocket

See: [AMQP Sender for SAP Event Mesh](amqp-sender-for-sap-event-mesh-7d8a83f.md)



</td>
</tr>
<tr>
<td valign="top">

*AMQP for SAP Event Mesh*

Receiver adapter



</td>
<td valign="top">

Enables SAP Integration Suite to send messages to queues or topics in SAP Event Mesh.

Supported message protocol: AMQP \(Advanced Message Queuing Protocol\) 1.0

Supported transport protocol: WebSocket

See: [AMQP Receiver for SAP Event Mesh](amqp-receiver-for-sap-event-mesh-0b7cc2f.md)



</td>
</tr>
<tr>
<td valign="top">

*AMQP for Microsoft Azure Service Bus*

Sender adapter



</td>
<td valign="top">

Enables SAP Integration Suite to consume messages from queues or topic subscriptions in Microsoft Azure Service Bus.

Supported message protocol: AMQP \(Advanced Message Queuing Protocol\) 1.0

Supported transport protocol: TCP

See: [AMQP Sender for Microsoft Azure Service Bus](amqp-sender-for-microsoft-azure-service-bus-7384ac3.md)



</td>
</tr>
<tr>
<td valign="top">

*AMQP for Microsoft Azure Service Bus*

Receiver adapter



</td>
<td valign="top">

Enables SAP Integration Suite to send messages to queues or topics in Microsoft Azure Service Bus.

Supported message protocol: AMQP \(Advanced Message Queuing Protocol\) 1.0

Supported transport protocol: TCP

See: [AMQP Receiver for Microsoft Azure Service Bus](amqp-receiver-for-microsoft-azure-service-bus-9c64d80.md)



</td>
</tr>
<tr>
<td valign="top">

*AMQP for Solace PubSub+*

Sender adapter



</td>
<td valign="top">

Enables SAP Integration Suite to consume messages from queues or topic subscriptions in Solace PubSub+.

Supported message protocol: AMQP \(Advanced Message Queuing Protocol\) 1.0

Supported transport protocol: TCP

See: [AMQP Sender for Solace PubSub+](amqp-sender-for-solace-pubsub-c9ab47d.md)



</td>
</tr>
<tr>
<td valign="top">

*AMQP for Solace PubSub+*

Receiver adapter



</td>
<td valign="top">

Enables SAP Integration Suite to send messages to queues or topics in Solace PubSub+.

Supported message protocol: AMQP \(Advanced Message Queuing Protocol\) 1.0

Supported transport protocol: TCP

See: [AMQP Receiver for Solace PubSub+](amqp-receiver-for-solace-pubsub-19f18d8.md)



</td>
</tr>
<tr>
<td valign="top">

*AMQP for Apache Qpid Broker-J*

Sender adapter



</td>
<td valign="top">

Enables SAP Integration Suite to consume messages from queues or topic subscriptions in Apache Qpid Broker-J.

Supported message protocol: AMQP \(Advanced Message Queuing Protocol\) 1.0

Supported transport protocol: TCP, WebSocket

See: [AMQP Sender for Apache Qpid Broker-J](amqp-sender-for-apache-qpid-broker-j-b4983f7.md)



</td>
</tr>
<tr>
<td valign="top">

*AMQP for Apache Qpid Broker-J*

Receiver adapter



</td>
<td valign="top">

Enables SAP Integration Suite to send messages to queues or topics in Apache Qpid Broker-J.

Supported message protocol: AMQP \(Advanced Message Queuing Protocol\) 1.0

Supported transport protocol: TCP, WebSocket

See: [AMQP Receiver for Apache Qpid Broker-J](amqp-receiver-for-apache-qpid-broker-j-622aa1d.md)



</td>
</tr>
<tr>
<td valign="top">

*AMQP for Apache ActiveMQ 5 / Apache ActiveMQ Artemis*

Sender adapter



</td>
<td valign="top">

Enables SAP Integration Suite to consume messages from queues or topic subscriptions in Apache ActiveMQ 5 / Apache ActiveMQ Artemis.

Supported message protocol: AMQP \(Advanced Message Queuing Protocol\) 1.0

Supported transport protocol: TCP

See: [AMQP Sender for Apache ActiveMQ 5 and Apache ActiveMQ Artemis](amqp-sender-for-apache-activemq-5-and-apache-activemq-artemis-dc4c564.md)



</td>
</tr>
<tr>
<td valign="top">

*AMQP for Apache ActiveMQ 5 / Apache ActiveMQ Artemis*

Receiver adapter



</td>
<td valign="top">

Enables SAP Integration Suite to send messages to queues or topics in Apache ActiveMQ 5 / Apache ActiveMQ Artemis.

Supported message protocol: AMQP \(Advanced Message Queuing Protocol\) 1.0

Supported transport protocol: TCP

See: [AMQP Receiver for Apache ActiveMQ 5 and Apache ActiveMQ Artemis](amqp-receiver-for-apache-activemq-5-and-apache-activemq-artemis-76c4dd3.md)



</td>
</tr>
<tr>
<td valign="top">

*AMQP for IBM MQ*

Sender adapter



</td>
<td valign="top">

Enables SAP Integration Suite to consume messages from queues or topic subscriptions in IBM MQ.

Supported message protocol: AMQP \(Advanced Message Queuing Protocol\) 1.0

Supported transport protocol: TCP

See: [AMQP Sender for IBM MQ](amqp-sender-for-ibm-mq-f6cc0e4.md)



</td>
</tr>
<tr>
<td valign="top">

*AMQP for IBM MQ*

Receiver adapter



</td>
<td valign="top">

Enables SAP Integration Suite to send messages to queues or topics in IBM MQ.

Supported message protocol: AMQP \(Advanced Message Queuing Protocol\) 1.0

Supported transport protocol: TCP

See: [AMQP Receiver for IBM MQ](amqp-receiver-for-ibm-mq-990fa99.md)



</td>
</tr>
<tr>
<td valign="top">

*Ariba*

Sender adapter



</td>
<td valign="top">

Connects SAP Integration Suite to the Ariba Network. Using this adapter, SAP and non-SAP cloud applications can receive business-specific documents in commerce eXtensible Markup Language \(cXML\) format from the Ariba network.

The sender adapter allows you to define a schedule for polling data from Ariba.

See: [Configure the Ariba Sender Adapter](https://help.sap.com/viewer/987273656c2f47d2aca4e0bfce26c594/Cloud/en-US/0629b58d4a764a0b8bcf9aa884503e78.html "The Ariba sender adapter connects SAP Cloud Integration to the Ariba Network. Using this adapter, SAP and non-SAP cloud applications can receive business-specific documents in commerce eXtensible Markup Language (cXML) format from the Ariba network. The sender adapter allows you to define a schedule for polling data from Ariba.") :arrow_upper_right:



</td>
</tr>
<tr>
<td valign="top">

*Ariba*

Receiver adapter



</td>
<td valign="top">

Connects SAP Integration Suite to the Ariba network. Using this adapter, SAP and non-SAP cloud applications can send business-specific documents in commerce eXtensible Markup Language \(cXML\) format to the Ariba network.Receiver adapter

See: [Configure the Ariba Receiver Adapter](https://help.sap.com/viewer/987273656c2f47d2aca4e0bfce26c594/Cloud/en-US/49dffa3da5784b7bb5dd6d8bf975939c.html "The Ariva receiver adapter connects SAP Cloud Integration to the Ariba network. Using this adapter, SAP and non-SAP cloud applications can send business-specific documents in commerce eXtensible Markup Language (cXML) format to the Ariba network.") :arrow_upper_right:



</td>
</tr>
<tr>
<td valign="top">

*AS2*

Sender adapter



</td>
<td valign="top">

Enables SAP Integration Suite to exchange business-specific documents with a partner through the Applicability Statement 2 \(AS2\) protocol.

Sender adapter: Can return an electronic receipt to the sender of the AS2 message \(in the form of a Message Disposition Notification \(MDN\)\)

See: [Configure the AS2 Sender Adapter](configure-the-as2-sender-adapter-5d7ee17.md)



</td>
</tr>
<tr>
<td valign="top">

*AS2*

Receiver adapter



</td>
<td valign="top">

Enables SAP Integration Suite to exchange business-specific documents with a partner through the Applicability Statement 2 \(AS2\) protocol.

See: [Configure the AS2 Receiver Adapter](configure-the-as2-receiver-adapter-9db62be.md)



</td>
</tr>
<tr>
<td valign="top">

*AS4*

Sender adapter



</td>
<td valign="top">

Enables SAP Integration Suite to securely process incoming AS4 messages using Web Services. The AS4 sender adapter is based on the ebMS 3.0 specification that supports the ebMS handler conformance profile.

-   Supports one-way/ebMS3 push message exchange pattern \(MEP\).

-   Support on-way/ebMS3 pull that allows the message party to pick the corresponding message from the partner.

-   Supports signature verification and decryption of the message.

-   Generates receipts after processing the incoming AS4 message.

-   Allows you to set a size limit for the body and attachment of an incoming message.


See: [AS4 Sender Adapter](as4-sender-adapter-a448605.md)



</td>
</tr>
<tr>
<td valign="top">

*AS4*

Receiver adapter



</td>
<td valign="top">

Enables SAP Integration Suite to establish a connection between any two message service handlers \(MSHs\) for exchanging business documents. The AS4 receiver adapter uses the Light Client conformance policy and supports only message pushing for the sending MSH and selective message pulling for the receiving MSH.

Receiver adapter:

-   Supports one-way/push message exchange pattern \(MEP\) that involves the transfer of business documents from a sending MSH to a receiving MSH.

-   Supports one-way/selective-pull message exchange pattern \(MEP\) that involves the receiving MSH initiating a selective pull request to the sending MSH. The sending MSH responds by sending the specific user message.

-   Supports storing and verification of receipts.


See: [AS4 Receiver Adapter](as4-receiver-adapter-3a2fde8.md)



</td>
</tr>
<tr>
<td valign="top">

*Data Store*

Sender adapter



</td>
<td valign="top">

Enables SAP Integration Suite to consume messages from a data store.

See: [Data Store Sender Adapter](data-store-sender-adapter-4f5ef3f.md)



</td>
</tr>
<tr>
<td valign="top">

*Dropbox*

Sender adapter



</td>
<td valign="top">

Enables SAP Integration Suite to receive files from the Dropbox storage.

See: [Configure the Dropbox Sender Adapter](configure-the-dropbox-sender-adapter-de61991.md)



</td>
</tr>
<tr>
<td valign="top">

*Dropbox*

Receiver adapter



</td>
<td valign="top">

Enables SAP Integration Suite to write files and folders to the Dropbox storage.

See: [Configure the Dropbox Receiver Adapter](configure-the-dropbox-receiver-adapter-16ef7b4.md)



</td>
</tr>
<tr>
<td valign="top">

*ELSTER*

Receiver adapter



</td>
<td valign="top">

Enables SAP Integration Suite to send a tax document to the ELSTER server.

ELSTER \(acronym for the German term *Elektronische Steuererklärung*\) is used in German fiscal management to process tax declarations exchanged over the Internet.

The adapter supports the following operations: Getting the version of the ERiC \(ELSTER Rich Client\) library, validating a tax document, and sending a tax document.

See: [ELSTER Receiver Adapter](elster-receiver-adapter-e374ef7.md)



</td>
</tr>
<tr>
<td valign="top">

*Facebook*

Receiver adapter



</td>
<td valign="top">

Enables SAP Integration Suite to access and extract information from Facebook based on certain criteria such as keywords or user data.

Using OAuth, the SAP BTP tenant can access resources on Facebook on behalf of a Facebook user.

See: [Facebook Receiver Adapter](https://help.sap.com/viewer/987273656c2f47d2aca4e0bfce26c594/Cloud/en-US/3dcc4080897c4bd4bf55bb8bf1bcac0d.html "You use the Facebook receiver adapter to extract information from Facebook (which is the receiver platform) based on certain criteria such as keywords, user data, for example. As one example, you can use this feature in social marketing activities to do social media data analysis based on Facebook content.") :arrow_upper_right:



</td>
</tr>
<tr>
<td valign="top">

*FTP*

Sender adapter



</td>
<td valign="top">

Enables SAP Integration Suite to connect to a remote system using TCP \(Transmission Control Protocol\) to receive files from the system.

FTP stands for File Transfer Protocol.

The sender adapter allows you to define a schedule for polling data from the connected system.

See: [Configure the FTP Sender Adapter](configure-the-ftp-sender-adapter-239042f.md)



</td>
</tr>
<tr>
<td valign="top">

*FTP*

Receiver adapter



</td>
<td valign="top">

Enables SAP Integration Suite to connect to a remote system using TCP \(Transmission Control Protocol\) to write files to the system.

FTP stands for File Transfer Protocol.

See: [Configure the FTP Receiver Adapter](configure-the-ftp-receiver-adapter-c16d331.md)



</td>
</tr>
<tr>
<td valign="top">

*HTTPS*

Sender adapter



</td>
<td valign="top">

Establishes an HTTPS connection between SAP Integration Suite and a sender system.

See: [HTTPS Sender Adapter](https-sender-adapter-0ae4a78.md)



</td>
</tr>
<tr>
<td valign="top">

*HTTP*

Receiver adapter



</td>
<td valign="top">

Establishes an HTTP connection between SAP Integration Suite and a receiver system.

Receiver adapter:

-   Supports HTTP 1.1 only \(target system must support chunked transfer encoding and may not rely on the existence of the HTTP Content-Length header\)

-   Supports the following methods: DELETE, GET, HEAD, POST, PUT, TRACE

    Method can also be determined dynamically by reading a value from a message header or property during runtime.


See: [HTTP Receiver Adapter](http-receiver-adapter-2da452e.md)



</td>
</tr>
<tr>
<td valign="top">

*IDoc*

Sender adapter



</td>
<td valign="top">

Allows SAP Integration Suite to exchange Intermediate Document \(IDoc\) messages with a sender system that supports communication via SOAP Web services.

A size limit for the inbound message can be configured for the sender adapter.

See: [Configure the IDoc Sender Adapter](configure-the-idoc-sender-adapter-bf769d6.md)



</td>
</tr>
<tr>
<td valign="top">

*IDoc*

Receiver adapter



</td>
<td valign="top">

Allows SAP Integration Suite to exchange Intermediate Document \(IDoc\) messages with a receiver system that supports communication via SOAP Web services.

See: [Configure the IDoc Receiver Adapter](configure-the-idoc-receiver-adapter-018aa88.md)



</td>
</tr>
<tr>
<td valign="top">

*JDBC*

Receiver adapter



</td>
<td valign="top">

Allows SAP Integration Suite to connect to a JDBC \(Java Database Connectivity\) database and to execute SQL commands on the database.

See: [JDBC Receiver Adapter](jdbc-receiver-adapter-88be644.md)



</td>
</tr>
<tr>
<td valign="top">

*JDBC for DB2 \(On-Premise\)*

Receiver adapter



</td>
<td valign="top">

Allows SAP Integration Suite to connect to DB2 \(On-Premise\) using JDBC \(Java Database Connectivity\) and to execute SQL commands on the database.

See: [JDBC for DB2 \(On-Premise\)](jdbc-for-db2-on-premise-9515cf8.md)



</td>
</tr>
<tr>
<td valign="top">

*JDBC for Microsoft SQL Server \(Cloud\)*

Receiver adapter



</td>
<td valign="top">

Allows SAP Integration Suite to connect to Microsoft SQL Server \(Cloud\) using JDBC \(Java Database Connectivity\) and to execute SQL commands on the database.

See: [JDBC for Microsoft SQL Server \(Cloud\)](jdbc-for-microsoft-sql-server-cloud-4173d0a.md)



</td>
</tr>
<tr>
<td valign="top">

*JDBC for Microsoft SQL Server \(On-Premise\)*

Receiver adapter



</td>
<td valign="top">

Allows SAP Integration Suite to connect to Microsoft SQL Server \(On-Premise\) using JDBC \(Java Database Connectivity\) and to execute SQL commands on the database.

See: [JDBC for Microsoft SQL Server \(On-Premise\)](jdbc-for-microsoft-sql-server-on-premise-9745e40.md)



</td>
</tr>
<tr>
<td valign="top">

*JDBC for Oracle \(Cloud\)*

Receiver adapter



</td>
<td valign="top">

Allows SAP Integration Suite to connect to Oracle \(Cloud\) using JDBC \(Java Database Connectivity\) and to execute SQL commands on the database.

See: [JDBC for Oracle \(Cloud\)](jdbc-for-oracle-cloud-f868182.md)



</td>
</tr>
<tr>
<td valign="top">

*JDBC for Oracle \(On-Premise\)*

Receiver adapter



</td>
<td valign="top">

Allows SAP Integration Suite to connect to Oracle \(On-Premise\) using JDBC \(Java Database Connectivity\) and to execute SQL commands on the database.

See: [JDBC for Oracle \(On-Premise\)](jdbc-for-oracle-on-premise-e6db38a.md)



</td>
</tr>
<tr>
<td valign="top">

*JDBC for PostgreSQL \(Cloud\)*

Receiver adapter



</td>
<td valign="top">

Allows SAP Integration Suite to connect to PostgreSQL \(Cloud\) using JDBC \(Java Database Connectivity\) and to execute SQL commands on the database.

See: [JDBC for PostgreSQL \(Cloud\)](jdbc-for-postgresql-cloud-4d5b488.md)



</td>
</tr>
<tr>
<td valign="top">

*JDBC for SAP ASE Service \(Neo\)*

Receiver adapter



</td>
<td valign="top">

Allows SAP Integration Suite to connect to SAP ASE Service \(Neo\) using JDBC \(Java Database Connectivity\) and to execute SQL commands on the database.

See: [JDBC for SAP ASE Service \(Neo\)](jdbc-for-sap-ase-service-neo-a6271cc.md)



</td>
</tr>
<tr>
<td valign="top">

*JDBC for SAP HANA Cloud*

Receiver adapter



</td>
<td valign="top">

Allows SAP Integration Suite to connect to SAP HANA Cloud using JDBC \(Java Database Connectivity\) and to execute SQL commands on the database.

See: [JDBC for SAP HANA Cloud](jdbc-for-sap-hana-cloud-187a8e8.md)



</td>
</tr>
<tr>
<td valign="top">

*JDBC for SAP HANA Platform \(On-Premise\)*

Receiver adapter



</td>
<td valign="top">

Allows SAP Integration Suite to connect to SAP HANA Platform \(On-Premise\) using JDBC \(Java Database Connectivity\) and to execute SQL commands on the database.

See: [JDBC for SAP HANA Platform \(On-Premise\)](jdbc-for-sap-hana-platform-on-premise-ff29388.md)



</td>
</tr>
<tr>
<td valign="top">

*JDBC for SAP HANA Service \(Neo\)*

Receiver adapter



</td>
<td valign="top">

Allows SAP Integration Suite to connect to SAP HANA Service \(Neo\) using JDBC \(Java Database Connectivity\) and to execute SQL commands on the database.

See: [JDBC for SAP HANA Service \(Neo\)](jdbc-for-sap-hana-service-neo-030e47e.md)



</td>
</tr>
<tr>
<td valign="top">

*JMS* 

Sender adapter



</td>
<td valign="top">

Enables asynchronous messaging by using message queues.

The sender adapter consumes messages from a queue. The messages are processed concurrently.

To prevent situations where the JMS adapter tries again and again to process a failed \(large\) message, you can store messages \(where the processing stopped unexpectedly\) in a dead-letter queue after two retries.

Certain constraints apply with regard to the number and capacity of involved queues, as well as for the headers and exchange properties defined in the integration flow before the message is saved to the queue \(as described in the product documentation\).

See: [Configure the JMS Sender Adapter](https://help.sap.com/viewer/987273656c2f47d2aca4e0bfce26c594/Cloud/en-US/161791b8cb98485ba00d81efa4197a49.html "The JMS sender adapter enables asynchronous decoupling of inbound and outbound processing by using message queues. The sender adapter consumes messages from a JMS queue.") :arrow_upper_right:



</td>
</tr>
<tr>
<td valign="top">

*JMS*

Receiver adapter



</td>
<td valign="top">

Enables asynchronous messaging by using message queues.

The receiver adapter stores messages and schedules them for processing in a queue. The messages are processed concurrently.

See: [Configure the JMS Receiver Adapter](https://help.sap.com/viewer/987273656c2f47d2aca4e0bfce26c594/Cloud/en-US/79edc04c91574a6bb8c15ae3e1a27b03.html "The JMS receiver adapter enables asynchronous decoupling of inbound and outbound processing by using message queues. The receiver adapter stores messages and schedules them for processing in a queue. The messages are processed concurrently.") :arrow_upper_right:



</td>
</tr>
<tr>
<td valign="top">

*Kafka*

Sender adapter



</td>
<td valign="top">

Allows SAP Integration Suite to connect to an external Kafka broker via Kafka protocol and to fetch Kafka records \(messages\).

See: [Configure the Kafka Sender Adapter](configure-the-kafka-sender-adapter-0d849e5.md)



</td>
</tr>
<tr>
<td valign="top">

*Kafka*

Receiver adapter



</td>
<td valign="top">

Allows SAP Integration Suite to connect to an external Kafka broker via Kafka protocol and to send Kafka records \(messages\).

See: [Configure the Kafka Receiver Adapter](configure-the-kafka-receiver-adapter-fc6ee1f.md)



</td>
</tr>
<tr>
<td valign="top">

*Mail Sender for IMAP*

Sender adapter



</td>
<td valign="top">

Enables SAP Integration Suite to read e-mails from an e-mail server using the Internet Message Access Protocol \(IMAP\) protocol.

To authenticate against the e-mail server, you can send the user name and password in plain text or encrypted \(the latter only if the e-mail server supports this option\).

You can protect inbound e-mails at the transport layer with IMAPS and STARTTLS.

The sender adapter allows you to define a schedule for polling data from the connected system.

For more information on possible threats when processing e-mail content with the Mail adapter, see the product documentation.

See: [Mail Sender for IMAP](mail-sender-for-imap-5b94e42.md)



</td>
</tr>
<tr>
<td valign="top">

*Mail Sender for POP3*

Sender adapter



</td>
<td valign="top">

Enables SAP Integration Suite to read e-mails from an e-mail server using the Post Office Protocol \(POP3\) protocol.

To authenticate against the e-mail server, you can send the user name and password in plain text or encrypted \(the latter only if the e-mail server supports this option\).

You can protect inbound e-mails at the transport layer with POP3S and STARTTLS.

The sender adapter allows you to define a schedule for polling data from the connected system.

For more information on possible threats when processing e-mail content with the Mail adapter, see the product documentation.

See: [Mail Sender for POP3](mail-sender-for-pop3-c52a4da.md)



</td>
</tr>
<tr>
<td valign="top">

*Mail*

Receiver adapter



</td>
<td valign="top">

Enables SAP Integration Suite to send e-mails to an e-mail server.

To authenticate against the e-mail server, you can send the user name and password in plain text or encrypted \(the latter only if the e-mail server supports this option\).

-   You can protect outbound e-mails at the transport layer with STARTTLS or SMTPS.

-   You can encrypt outbound e-mails using S/MIME \(supported content encryption algorithms: AES/CBC/PKCS5Padding, DESede/CBC/PKCS5Padding\).


See: [Configure the Mail Receiver Adapter](configure-the-mail-receiver-adapter-f68d5e0.md)



</td>
</tr>
<tr>
<td valign="top">

*MDI* 

Receiver adapter

\(only available in the Cloud Foundry environment\)



</td>
<td valign="top">

The MDI \(SAP Master Data Integration\) adapter synchronizes your master data from SAP applications like SAP ECC and other third party applications with SAP MDI service.

See: [MDI Receiver Adapter](mdi-receiver-adapter-e91e373.md)



</td>
</tr>
<tr>
<td valign="top">

*Microsoft Dynamics CRM* 

Receiver adapter



</td>
<td valign="top">

Connects SAP Integration Suite to Microsoft Dynamics Customer Relationship Management \(CRM\).

See: [Microsoft Dynamics CRM Receiver Adapter](microsoft-dynamics-crm-receiver-adapter-ee724c8.md)



</td>
</tr>
<tr>
<td valign="top">

*OData* 

Sender adapter



</td>
<td valign="top">

Connects SAP Integration Suite to systems using the Open Data \(OData\) protocol in either ATOM or JSON format \(only synchronous communication is supported\).

Supported versions: OData version 2.0

-   The adapter receives incoming requests in either ATOM or JSON format.

-   Supported operations: Create \(POST\), Delete \(DELETE\), Query \(GET\), Read \(GET\), Update \(PUT\)

    Using the GET or POST method, the sender adapter can also invoke operations that are not covered by the standard CRUD \(Create, Retrieve, Update, and Delete\) methods \(function import\).


See: [Configure the OData Sender Adapter](configure-the-odata-sender-adapter-de7aee5.md)



</td>
</tr>
<tr>
<td valign="top">

*OData*

Receiver adapter



</td>
<td valign="top">

Connects SAP Integration Suite to systems using the Open Data \(OData\) protocol.

Supported versions:

-   OData version 2.0

    Supported operations: Create \(POST\), Delete \(DELETE\), Merge \(MERGE\), Query \(GET\), Read \(GET\), Update \(PUT\), Patch \(PATCH\)

-   OData version 4.0

    Supported operations: Create \(POST\), Query \(GET\), Update \(PUT\)

-   The outgoing request payload must be in XML format.


See:

-   [Configure the OData V2 Receiver Adapter](configure-the-odata-v2-receiver-adapter-c5c2e38.md)

-   [Configure the OData V4 Receiver Adapter](configure-the-odata-v4-receiver-adapter-cd66a12.md)




</td>
</tr>
<tr>
<td valign="top">

*ODC*

Receiver adapter



</td>
<td valign="top">

Connects SAP Integration Suite to SAP Gateway OData Channel \(through transport protocol HTTPS\).

Supported operations: Create \(POST\), Delete \(DELETE\), Merge \(MERGE\), Query \(GET\), Read \(GET\), Update \(PUT\)

See: [ODC Receiver Adapter](odc-receiver-adapter-3cdbc29.md)



</td>
</tr>
<tr>
<td valign="top">

*OpenConnectors*

Receiver adapter



</td>
<td valign="top">

Connects SAP Integration Suite to more than 150 non-SAP Cloud applications that are supported by SAP Open Connectors.

-   Uses APIs to fetch data from specific third-party applications.

-   Is designed to handle large volumes of incoming data.

-   Supports messages in both JSON and XML format, for request and response calls.

-   Allows you to define specific values for variables.


See: [OpenConnectors Receiver Adapter](openconnectors-receiver-adapter-1a27cee.md)



</td>
</tr>
<tr>
<td valign="top">

*ProcessDirect*

Sender adapter



</td>
<td valign="top">

Connects an integration flow with another integration flow deployed on the same tenant.

An integration flow with a ProcessDirect sender adapter \(as consumer\) consumes data from another integration flow.

N:1 cardinality of producer and consumer integration flows is supported.

See: [Configure the ProcessDirect Sender Adapter](configure-the-processdirect-sender-adapter-e340d4c.md)



</td>
</tr>
<tr>
<td valign="top">

*ProcessDirect*

Receiver adapter



</td>
<td valign="top">

Connects an integration flow with another integration flow deployed on the same tenant.

An integration flow with a ProcessDirect receiver adapter \(as producer\) sends data to another integration flow.

N:1 cardinality of producer and consumer integration flows is supported.

See: [Configure the ProcessDirect Receiver Adapter](configure-the-processdirect-receiver-adapter-5b7327d.md)



</td>
</tr>
<tr>
<td valign="top">

*RFC*

Receiver adapter



</td>
<td valign="top">

Connects SAP Integration Suite to a remote receiver system using Remote Function Call \(RFC\).

RFC is the standard interface used for integrating on-premise ABAP systems to the systems hosted on the cloud using SAP Cloud Connector.

The adapter supports SAP NetWeaver, version 7.31 or higher.

See: [RFC Receiver Adapter](rfc-receiver-adapter-5c76048.md)



</td>
</tr>
<tr>
<td valign="top">

*Salesforce* 

Sender adapter



</td>
<td valign="top">

Connects SAP Integration Suite to Salesforce.

See: [Salesforce Sender Adapter](salesforce-sender-adapter-ba6420d.md)



</td>
</tr>
<tr>
<td valign="top">

*Salesforce* 

Receiver adapter



</td>
<td valign="top">

Connects SAP Integration Suite to Salesforce.

See: [Salesforce Receiver Adapter](salesforce-receiver-adapter-a548be9.md)



</td>
</tr>
<tr>
<td valign="top">

*ServiceNow* 

Receiver adapter



</td>
<td valign="top">

Connects SAP Integration Suite to ServiceNow. Supports basic authentication and OAuth.

See: [ServiceNow Receiver Adapter](servicenow-receiver-adapter-1e3bcf4.md)



</td>
</tr>
<tr>
<td valign="top">

*SFTP* 

Sender adapter



</td>
<td valign="top">

Connects SAP Integration Suite to a remote system using the SSH File Transfer protocol to read files from the system. SSH File Transfer protocol is also referred to as Secure File Transfer protocol \(or SFTP\).

Supported versions:

SSH version 2 \(as specified at [http://tools.ietf.org/html/rfc4251](http://tools.ietf.org/html/rfc4251)\), SSH File Transfer Protocol \(SFTP\) version 3 or higher

The sender adapter allows you to define a schedule for polling data from the connected system.

See: [Configure the SFTP Sender Adapter](configure-the-sftp-sender-adapter-2de9ee5.md)



</td>
</tr>
<tr>
<td valign="top">

*SFTP*

Receiver adapter



</td>
<td valign="top">

Connects SAP Integration Suite to a remote system using the SSH File Transfer protocol to write files to the system. SSH File Transfer protocol is also referred to as Secure File Transfer protocol \(or SFTP\).

Supported versions:

SSH version 2 \(as specified at [http://tools.ietf.org/html/rfc4251](http://tools.ietf.org/html/rfc4251)\), SSH File Transfer Protocol \(SFTP\) version 3 or higher

See: [Configure the SFTP Receiver Adapter](configure-the-sftp-receiver-adapter-4ef52cf.md)



</td>
</tr>
<tr>
<td valign="top">

*SOAP SOAP 1.x* 

Sender adapter



</td>
<td valign="top">

Exchanges messages with a sender system that supports Simple Object Access Protocol \(SOAP\) 1.1 or SOAP 1.2.

The message exchange patterns supported by the sender adapter are one-way messaging or request-reply.

The adapter supports Web services Security \(WS-Security\).

A size limit for the inbound message can be configured for the sender adapter.

See: [Configure the SOAP \(SOAP 1.x\) Sender Adapter](configure-the-soap-soap-1-x-sender-adapter-a178913.md)



</td>
</tr>
<tr>
<td valign="top">

*SOAP SOAP 1.x*

Receiver adapter



</td>
<td valign="top">

Exchanges messages with a receiver system that supports Simple Object Access Protocol \(SOAP\) 1.1 or SOAP 1.2.

The adapter supports Web services Security \(WS-Security\).

See: [Configure the SOAP \(SOAP 1.x\) Receiver Adapter](configure-the-soap-soap-1-x-receiver-adapter-57f7b34.md)



</td>
</tr>
<tr>
<td valign="top">

*SOAP SAP RM* 

Sender adapter



</td>
<td valign="top">

Exchanges messages with a sender system based on the SOAP communication protocol and SAP Reliable Messaging \(SAP RM\) as the message protocol. SAP RM is a simplified communication protocol for asynchronous Web service communication that does not require the use of Web Service Reliable Messaging standards.

A size limit for the inbound message can be configured for the sender adapter.

See: [Configure the SOAP \(SAP RM\) Sender Adapter](configure-the-soap-sap-rm-sender-adapter-6962234.md)



</td>
</tr>
<tr>
<td valign="top">

*SOAP SAP RM* 

Receiver adapter



</td>
<td valign="top">

Exchanges messages with a receiver system based on the SOAP communication protocol and SAP Reliable Messaging \(SAP RM\) as the message protocol. SAP RM is a simplified communication protocol for asynchronous Web service communication that does not require the use of Web Service Reliable Messaging standards.

See: [Configure the SOAP \(SAP RM\) Receiver Adapter](configure-the-soap-sap-rm-receiver-adapter-8366495.md)



</td>
</tr>
<tr>
<td valign="top">

*SuccessFactors REST*

Sender adapter



</td>
<td valign="top">

Connects SAP Integration Suite to a SuccessFactors sender system using the REST message protocol.

The adapter supports the following operations: GET

See: [Configure the SuccessFactors \(REST\) Sender Adapter](configure-the-successfactors-rest-sender-adapter-9f0646b.md)



</td>
</tr>
<tr>
<td valign="top">

*SuccessFactors REST*

Receiver adapter



</td>
<td valign="top">

Connects SAP Integration Suite to a SuccessFactors receiver system using the REST message protocol.

The adapter supports the following operations: GET, POST

See: [Configure the SuccessFactors \(REST\) Receiver Adapter](configure-the-successfactors-rest-receiver-adapter-9cff562.md)



</td>
</tr>
<tr>
<td valign="top">

*SuccessFactors SOAP*

Sender adapter



</td>
<td valign="top">

Connects SAP Integration Suite to SOAP-based Web services of a SuccessFactors sender system \(synchronous or asynchronous communication\).

The adapter supports the following operations: Query

See: [Configure the SuccessFactors \(SOAP\) Sender Adapter](configure-the-successfactors-soap-sender-adapter-874e4b1.md)



</td>
</tr>
<tr>
<td valign="top">

*SuccessFactors SOAP*

Receiver adapter



</td>
<td valign="top">

Connects SAP Integration Suite to SOAP-based Web services of a SuccessFactors receiver system \(synchronous or asynchronous communication\).

The adapter supports the following operations: Insert, Query, Update, Upsert

See: [Configure the SuccessFactors SOAP Receiver Adapter](configure-the-successfactors-soap-receiver-adapter-360ef42.md)



</td>
</tr>
<tr>
<td valign="top">

*SuccessFactors OData V2*

Receiver adapter



</td>
<td valign="top">

Connects SAP Integration Suite to a SuccessFactors system using OData V2.

Features of OData version 2.0 supported by the adapter:

-   Operations: GET \(get single entity as an entry document\), PUT \(update existing entry with an entry document\), POST \(create new entry from an entry document\), DELETE \(Delete an entry from an entry document\), UPSERT \(combination of Update OR Insert\)

-   Query options: $expand, $skip,and $top

-   Server-side pagination

-   Client-side pagination

-   Pagination enhancement: Data retrieved in chunks and sent to Cloud Integration

-   Deep insert: Creates a structure of related entities in one request

-   Authentication options: Basic authentication

-   Reference links: Link two entities using the <link\> tag

See: [Configure the SuccessFactors OData V2 Receiver Adapter](configure-the-successfactors-odata-v2-receiver-adapter-d16dd12.md)



</td>
</tr>
<tr>
<td valign="top">

*SuccessFactors OData V4*

Receiver adapter



</td>
<td valign="top">

Connects SAP Integration Suite to a SuccessFactors system using OData V4.

Features of OData version 4.0 supported by the adapter:

-   Operations: GET, POST, PUT, DELETE

-   Navigation

-   Primitive types supported according to OData V4 specification

-   Structural types supported for create/update operations:

    Edm.ComplexType, Edm:EnumType, Collection\(Edm.PrimitiveType\) and Collection\(Edm.ComplexType\)


See: [SuccessFactors OData V4 Receiver Adapter](https://help.sap.com/viewer/987273656c2f47d2aca4e0bfce26c594/Cloud/en-US/cd091fc8051d42ee95eda2858ca2a2f0.html "The SuccessFactors receiver adapter enables you to communicate with the SuccessFactors system. You use the OData V4 message protocol to connect to the OData V4-based Web services of the SuccessFactors system.") :arrow_upper_right:



</td>
</tr>
<tr>
<td valign="top">

*SugarCRM* 

Receiver adapter



</td>
<td valign="top">

Connects SAP Integration Suite to SugarCRM.

See: [SugarCRM Receiver Adapter](sugarcrm-receiver-adapter-d96ddf7.md)



</td>
</tr>
<tr>
<td valign="top">

*Twitter* 

Receiver adapter



</td>
<td valign="top">

Enables SAP Integration Suite to access Twitter and read or post tweets.

Using OAuth, SAP Integration Suite can access resources on Twitter on behalf of a Twitter user.

See: [Twitter Receiver Adapter](https://help.sap.com/viewer/987273656c2f47d2aca4e0bfce26c594/Cloud/en-US/453c174be6ca4098a8c99dc4c1262d25.html "You use the Twitter receiver adapter to extract information from the Twitter platform based on certain criteria such as keywords, user data, for example. As one example, you can use this feature to send, search for and receive Twitter feeds.") :arrow_upper_right:



</td>
</tr>
<tr>
<td valign="top">

*Workday* 

Receiver adapter



</td>
<td valign="top">

Connects SAP Integration Suite to Workday. Supports Workday SOAP API with basic authentication.

See: [Workday Receiver Adapter](workday-receiver-adapter-0c6e670.md)



</td>
</tr>
<tr>
<td valign="top">

*XI*

Sender adapter



</td>
<td valign="top">

Connects SAP Integration Suite to a remote sender system that can process the XI message protocol.

See: [Configure the XI Sender Adapter](configure-the-xi-sender-adapter-41a1a57.md)



</td>
</tr>
<tr>
<td valign="top">

*XI*

Receiver adapter



</td>
<td valign="top">

Connects SAP Integration Suite to a remote receiver system that can process the XI message protocol.

See: [Configure the XI Receiver Adapter](configure-the-xi-receiver-adapter-5d2670f.md)



</td>
</tr>
</table>

If you are quick configuring an integration flow, you can configure a few adapter parameters. Refer to the relevant adapter configuration details for information on those parameters.

If you are developing an OData API, you can configure a SOAP, OData or HTTP adapter assigned to the receiver channel and the OData adapter assigned to the sender channel.

> ### Note:  
> **Note regarding the timeout behavior for HTTP communication:**
> 
> In HTTP communication spanning multiple components \(for example, from a sender, through the load balancer, to a Cloud Integration tenant, and from there to a receiver\), the actual timeout period is influenced by each of the timeout settings of the individual components that are interconnected between sender and receiver \(precisely spoken, of those components that can control the Transmission Control Protocol \(TCP\) session\). The component or device with the lowest number set for the idle session timeout will determine the timer that will be used.
> 
> -   When considering inbound communication \(through HTTP-based sender adapters\), note that in particular the load balancer has an own timeout setting that has an influence on the overall timeout. For the inbound side, SAP Cloud Integration supports no communication that waits for longer than 10 minutes.
> 
> -   When considering outbound communication, note that in the involved HTTP-based receiver channel you can configure a dedicated timeout. However, timeout setting has no influence on the TCP timeout when the receiver or any additional component interconnected between the Cloud Integration tenant and the receiver have a lower timeout. For example, consider that you have configured a receiver channel timeout of 10 minutes and there is another component involved with a timeout of 5 minutes. In case, nothing is transferred for a certain time, the connection will be closed after the 5th minute.

> ### Remember:  
> **Connecting to an on-premise system:**
> 
> When configuring a receiver adapter to connect with an on-premise system via SAP Cloud Connector, only connections/URLs with *<http://<virtual-url\>* in the SAP Cloud Connector are supported. The connection between Cloud Integration and cloud part of the SAP Cloud Connector happens inside an SAP BTP account, which is a secured digital space. Hence, *<http://<virtual-url\>* endpoints, instead of *<https://<virtual-url\>*, are sufficient.

**Related Information**  


[AMQP Adapter](amqp-adapter-5cc1a71.md "In many integration scenarios, messages or events have to be exchanged between applications or systems via message brokers. With the Advanced Message Queuing Protocol (AMQP) adapter, SAP Cloud Integration can be used as a provider or a consumer of such messages or events. Cloud Integration can connect to external message brokers using the AMQP protocol, consume messages or events using the AMQP sender adapter, or store messages or events in the message broker using the AMQP receiver adapter.")

[Ariba Adapter](https://help.sap.com/viewer/987273656c2f47d2aca4e0bfce26c594/Cloud/en-US/98da76c5d29348498e8b9e22ded9c028.html "You use this procedure to configure a sender and receiver channel of an integration flow with the Ariba Network adapter. These channels enable the SAP and non-SAP cloud applications to send and receive business-specific documents in cXML format to and from the Ariba Network. Examples of business documents are purchase orders and invoices.") :arrow_upper_right:

[AS2 Adapter](as2-adapter-d3af635.md "")

[AS4 Sender Adapter](as4-sender-adapter-a448605.md "You use AS4 message exchange protocol to securely process incoming business documents using Web services.")

[AS4 Receiver Adapter](as4-receiver-adapter-3a2fde8.md "Provides basic insights on how the AS4 messaging protocol enables message exchange between message service handlers (MSHs).")

[AmazonWebServices Sender Adapter](amazonwebservices-sender-adapter-16772e3.md "Amazon Web Services (AWS) sender adapter enables your SAP Cloud Integration tenant to do transfer of data with AWS cloud platform.")

[AmazonWebServices Receiver Adapter](amazonwebservices-receiver-adapter-bc7d1aa.md "Amazon Web Services (AWS) receiver adapter enables your SAP Cloud Integration tenant to do transfer of data with AWS cloud platform.")

[ELSTER Receiver Adapter](elster-receiver-adapter-e374ef7.md "This adapter enables an SAP BTP tenant to send a tax document to the ELSTER server.")

[Facebook Receiver Adapter](https://help.sap.com/viewer/987273656c2f47d2aca4e0bfce26c594/Cloud/en-US/3dcc4080897c4bd4bf55bb8bf1bcac0d.html "You use the Facebook receiver adapter to extract information from Facebook (which is the receiver platform) based on certain criteria such as keywords, user data, for example. As one example, you can use this feature in social marketing activities to do social media data analysis based on Facebook content.") :arrow_upper_right:

[FTP Adapter](ftp-adapter-4464f89.md "In many integration scenarios, messages or events have to be exchanged between applications or systems via FTP servers. The FTP adapter allows you to configure transport protocol FTP/FTPS for the connection to the FTP server to send messages to the FTP server or to receive messages from the FTP server.")

[HTTP Receiver Adapter](http-receiver-adapter-2da452e.md "Use the HTTP receiver adapter to communicate with target systems using HTTP message protocol.")

[HTTPS Sender Adapter](https-sender-adapter-0ae4a78.md "")

[IDoc Adapter](idoc-adapter-6042250.md "The IDoc adapter enables the SAP BTP tenant to exchange Intermediate Document (IDoc) messages with systems that support communication via SOAP Web services.")

[JDBC Receiver Adapter](jdbc-receiver-adapter-88be644.md "The JDBC (Java Database Connectivity) adapter enables you to connect Cloud Integration to cloud or on-premise databases.")

[JMS Adapter](https://help.sap.com/viewer/987273656c2f47d2aca4e0bfce26c594/Cloud/en-US/0993f2aa14124376a4adc7c5ba95d3f8.html "You configure the JMS adapter to enable asynchronous messaging using message queues.") :arrow_upper_right:

[Kafka Adapter](kafka-adapter-3e7b995.md "")

[LDAP Receiver Adapter](ldap-receiver-adapter-06a753f.md "The Lightweight Directory Access Protocol (LDAP) Receiver Adapter enables you to communicate with systems that expose data through LDAP service.")

[Mail Adapter](mail-adapter-f1145cc.md "The mail adapter allows you to connect the tenant to an email server. The sender mail adapter can download e-mails and access the e-mail body content as well as attachments. The receiver mail adapter allows you to send encrypted messages by e-mail.")

[Microsoft Dynamics CRM Receiver Adapter](microsoft-dynamics-crm-receiver-adapter-ee724c8.md "The Microsoft Dynamics CRM receiver adapter enables an SAP Cloud Integration tenant to accelerate the implementation time and reduce the complexity of connecting to Microsoft Dynamics CRM.")

[OData Adapter](odata-adapter-2d82511.md "The OData adapter allows you to communicate with an OData API using OData protocol. You use messages in ATOM or JSON format for communication. This OData adapter uses OData V2 message protocol.")

[ODC Receiver Adapter](odc-receiver-adapter-3cdbc29.md "he ODC adapter enables you to communicate with systems that expose data through the OData Channel for SAP Gateway.")

[OpenConnectors Receiver Adapter](openconnectors-receiver-adapter-1a27cee.md "You use the OpenConnectors receiver adapter in integration flows to communicate with more than 170 non-SAP cloud applications that are supported by Open Connectors.")

[ProcessDirect Adapter](processdirect-adapter-7445718.md "Use ProcessDirect adapter (sender and receiver) to establish fast and direct communication between integration flows by reducing latency and network overhead provided both of them are available within a same tenant.")

[RFC Receiver Adapter](rfc-receiver-adapter-5c76048.md "Connects an SAP Cloud Integration tenant to a remote receiver system using Remote Function Call (RFC).")

[Salesforce Receiver Adapter](salesforce-receiver-adapter-a548be9.md "The Salesforce receiver adapter enables an SAP Cloud Integration tenant to accelerate the implementation time and reduce the complexity of connecting to Salesforce.")

[ServiceNow Receiver Adapter](servicenow-receiver-adapter-1e3bcf4.md "ServiceNow receiver adapter enables SAP Cloud Integration and SAP Integration Suite to accelerate the implementation time and reduce the complexity of connecting to ServiceNow.")

[SFTP Adapter](sftp-adapter-e3dce88.md "Use SFTP adapter to encrypt and exchange sensitive business data between trading partners.")

[SOAP \(SAP RM\) Adapter](soap-sap-rm-adapter-6bd724f.md "You use this procedure to configure a communication channel with the SOAP (SAP RM) adapter.")

[SOAP \(SOAP 1.x\) Adapter](soap-soap-1-x-adapter-b847968.md "With this adapter, the tenant can exchange messages with another system that supports Simple Object Access Protocol (SOAP) 1.1 or SOAP 1.2.")

[SuccessFactors \(OData V2\) Adapter](successfactors-odata-v2-adapter-b27829c.md "")

[SuccessFactors OData V4 Receiver Adapter](https://help.sap.com/viewer/987273656c2f47d2aca4e0bfce26c594/Cloud/en-US/cd091fc8051d42ee95eda2858ca2a2f0.html "The SuccessFactors receiver adapter enables you to communicate with the SuccessFactors system. You use the OData V4 message protocol to connect to the OData V4-based Web services of the SuccessFactors system.") :arrow_upper_right:

[SuccessFactors \(REST\) Adapter](successfactors-rest-adapter-9df8cc6.md "The SuccessFactors adapter enables you to communicate with the SuccessFactors system. You use the REST message protocol to connect to the REST-based Web services of the SuccessFactors system.")

[SuccessFactors \(SOAP\) Adapter](successfactors-soap-adapter-28b29d6.md "The SuccessFactors adapter enables you to communicate with the SuccessFactors system. You use the SOAP message protocol to connect to the SOAP-based Web services of the SuccessFactors system.")

[SugarCRM Receiver Adapter](sugarcrm-receiver-adapter-d96ddf7.md "The SugarCRM receiver adapter enables an SAP Cloud Integration tenant to accelerate the implementation time and reduce the complexity of connecting to SugarCRM.")

[Twitter Receiver Adapter](https://help.sap.com/viewer/987273656c2f47d2aca4e0bfce26c594/Cloud/en-US/453c174be6ca4098a8c99dc4c1262d25.html "You use the Twitter receiver adapter to extract information from the Twitter platform based on certain criteria such as keywords, user data, for example. As one example, you can use this feature to send, search for and receive Twitter feeds.") :arrow_upper_right:

[Workday Receiver Adapter](workday-receiver-adapter-0c6e670.md "Workday receiver adapter enables SAP Cloud Integration and SAP Integration Suite to accelerate the implementation time and reduce the complexity of connecting to Workday.")

[XI Adapter](xi-adapter-8fedc92.md "The XI adapter connects an SAP Cloud Integration tenant to a remote system that can process the XI message protocol.")

