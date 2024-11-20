# Kafka-mini

This project is a simplified implementation of a Kafka broker. It sets up a server on port 9092, processes client requests, and handles ApiVersions requests based on the Kafka protocol. The implementation includes parsing the correlation_id and api_version from client messages and sending back appropriate responses, including error codes for unsupported versions. Scope is limited for now, maybe it'll be expanded in the future. 

---

 ### What I learnt :
 - low-level networking
 - protocol parsing
 - binary data handling in Java.
 - socket programming
 - error handling and debugging (protocol errors, response corrections)

---

### Where did I learn all that?
https://kafka.apache.org/protocol.html

---


### Future Scope : 
- concurrent clients
- listing partitions
- other apis (fetch etc)


