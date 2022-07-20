# day-01
# 1.Difference between HTTP1.1 vs HTTP2
# HTTP1.1
Ithe usest works on the textual format.	
There is head of line blocking that blocks all the requests behind it until it doesn’t get its all resources.	
It uses requests resource Inlining for use getting multiple pages	
It compresses data by itself.	
# HTTP2
It works on the binary protocol.
It allows multiplexing so one TCP connection is required for multiple requests.
It uses PUSH frame by server that collects all multiple pages 
It uses HPACK for data compression.
# 2.About of OBJECT
Objects, in JavaScript, is the most important data-type and forms the building blocks for modern JavaScript. These objects are quite different from JavaScript’s primitive data-types(Number, String, Boolean, null, undefined and symbol) in the sense that while these primitive data-types all store a single value each (depending on their types).
# Object interenal representation in javascript
let object_name = {
    key_name : value,
    ...
}
let school = {
    name : "Vivekananda School",
    location : "Delhi",
    established : "1971"
}
