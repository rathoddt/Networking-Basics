# Transport Layer

Layer 4 - Transport layer basics

### TLS/SSL offloading
By employing TLS/SSL offloading, the server can offload the burden of decrypting and encrypting traffic transmitted via SSL, resulting in improved performance and resource utilization.

<b>Types of TLS/SSL offloading</b>   
There are two different ways to accomplish TLS/SSL offloading.  

<i>TLS/SSL termination</i>  
TLS/SSL termination is the simpler approach of the two. In this process, encrypted traffic is intercepted before it hits your servers and decrypted on a dedicated TLS/SSL termination device instead of the application server. Then the decrypted data is forwarded on to the application server.

<i>TLS/SSL bridging  </i>
TLS/SSL bridging adds another layer of security by performing extra checks for malware. Incoming data is decrypted, inspected for malicious code, then is re-encrypted and sent on to the web server. This form of TLS/SSL offloading is meant to increase security rather than reduce processing activities on the application server.
