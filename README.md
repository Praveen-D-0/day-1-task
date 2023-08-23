 #  Question no:1
## Exploring the Differences between HTTP/1.1 and HTTP/2
In the rapidly evolving landscape of web development, the protocols that govern the way information is transferred between clients and servers have a significant impact on the performance and user experience of websites. Two major versions of the Hypertext Transfer Protocol (HTTP) that have shaped the modern web are HTTP/1.1 and HTTP/2. Let's delve into the key differences between these two protocols and understand how they have revolutionized web communication.

### Introduction to HTTP/1.1 and HTTP/2
HTTP/1.1, the stalwart of web communication, was first introduced in 1997. It ushered in an era of information exchange between clients (typically web browsers) and servers, allowing the internet to flourish. However, as the complexity and demands of websites grew over time, the limitations of HTTP/1.1 became more apparent, leading to the development of HTTP/2, which was standardized in 2015.

### Multiplexing and Concurrency
One of the most remarkable improvements that HTTP/2 brings to the table is multiplexing. Unlike its predecessor, which relied on multiple connections to transfer data, HTTP/2 enables multiplexing over a single connection. This means that multiple requests and responses can be interwoven within the same connection, eliminating the need to wait for a response before sending the next request. This drastic improvement in concurrency enhances the efficiency of data transmission.

### Header Compression
The headers of HTTP requests and responses contain important information about the data being transferred. In HTTP/1.1, these headers were sent in plaintext, leading to redundancy and increased latency. In contrast, HTTP/2 introduces header compression, where headers are efficiently encoded and decoded, reducing overhead and resulting in faster data transfers. This optimization contributes to a more streamlined communication process.

### Server Push
HTTP/2 introduces a feature known as server push, which allows the server to proactively send resources to the client before they are explicitly requested. For instance, if a client requests an HTML page, the server can push associated stylesheets and scripts to the client's cache. This preemptive action eliminates the need for the client to send additional requests for these resources, leading to faster page load times.

### Prioritization
While HTTP/1.1 treated all requests with the same level of importance, HTTP/2 allows for the prioritization of requests. This means that critical resources can be assigned a higher priority, ensuring that they are fetched and delivered to the client sooner. This feature greatly enhances the perceived speed of web pages as important content is prioritized over less critical resources.

### Binary Protocol
HTTP/1.1 utilized a text-based protocol, which was human-readable but not the most efficient for machines to process. HTTP/2, on the other hand, employs a binary protocol. This change reduces the complexity of parsing data and enables faster and more reliable communication between clients 
and servers.

### Backward Compatibility
A significant advantage of HTTP/2 is its seamless integration with existing systems. Servers that support HTTP/2 can still communicate with clients using HTTP/1.1, ensuring a smooth transition and backward compatibility for older systems and browsers.

### TLS Usage
Although not mandatory, HTTP/2 implementations often require the use of Transport Layer Security (TLS), which provides encryption and enhances security. While TLS was recommended for HTTP/1.1, it is more widely adopted in the context of HTTP/2, contributing to a safer browsing experience.

### Resource Loading
HTTP/1.1 often necessitated resource bundling to reduce the number of connections established. However, this approach could lead to inefficient use of resources. HTTP/2's multiplexing capabilities eliminate the need for bundling, enabling more granular resource loading and improving overall page load times.

### Impact on SEO
Website speed is a critical factor in search engine optimization (SEO). Given HTTP/2's inherent performance improvements, it indirectly affects SEO rankings positively. Search engines, including Google, consider page speed when determining search result rankings.

### Browser and Server Support
HTTP/2 enjoys broad support across modern web browsers and servers. While most current browsers support HTTP/2, older browser versions might not fully capitalize on its advantages. As for servers, major ones like Apache, NGINX, and IIS have incorporated HTTP/2 support.

### Migration Considerations
Migrating from HTTP/1.1 to HTTP/2 requires careful planning and configuration adjustments. The benefits are substantial, but a well-executed migration strategy is essential to avoid potential issues during the transition.

### Real-World Performance Improvements
Numerous performance benchmarks have illustrated the significant improvements that HTTP/2 brings to the table. Websites utilizing HTTP/2 exhibit faster load times, improved user engagement, and an enhanced overall browsing experience.

### Future Evolution
HTTP/2 sets the stage for the future of web communication protocols. Its adaptable architecture allows for the incorporation of new features and improvements, ensuring that it remains relevant and effective in meeting the evolving demands of the digital age.


### Conclusion
In the grand scheme of web development, the transition from HTTP/1.1 to HTTP/2 represents a paradigm shift. The advancements in multiplexing, header compression, prioritization, and other areas redefine the way we interact with the internet. While HTTP/2 has brought about monumental improvements, the journey doesn't end here. With HTTP/3 and beyond on the horizon, the trajectory of web communication is poised to reach even greater heights, offering users faster, safer, and more efficient online experiences.


 #  Question no:2
## Objects And Its Internal Representation In JavaScript
Objects, in JavaScript, is it’s most important data-type and forms the building blocks for modern JavaScript. These objects are quite different from JavaScript’s primitive data-types(Number, String, Boolean, null, undefined and symbol) in the sense that while these primitive data-types all store a single value each (depending on their types).

Objects are more complex and each object may contain any combination of these primitive data-types as well as reference data-types.
An object, is a reference data type. Variables that are assigned a reference value are given a reference or a pointer to that value. That reference or pointer points to the location in memory where the object is stored. The variables don’t actually store the value.

Loosely speaking, objects in JavaScript may be defined as an unordered collection of related data, of primitive or reference types, in the form of “key: value” pairs. These keys can be variables or functions and are called properties and methods, respectively, in the context of an object.

For Eg. If your object is a student, it will have properties like name, age, address, id, etc and methods like updateAddress, updateNam, etc.

### Objects and properties
A JavaScript object has properties associated with it. A property of an object can be explained as a variable that is attached to the object. Object properties are basically the same as ordinary JavaScript variables, except for the attachment to objects. The properties of an object define the characteristics of the object. You access the properties of an object with a simple dot-notation:

```javascript
objectName.propertyName

 