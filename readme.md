API at its core is a contract saying
- client: send me this *request*
- server: i'll send you this *response*

It's all about the data.

#### What is gRPC
- gRPC is a free, open-source framework developed by Google.
- It is part of the Cloud Native Computation Foudnation (CNCF), similar to Docker & Kubernetes

At high level, it allows you to define request and response calls for RPC (remote procedure calls), handling most stuff for you.
- Built on top of HTTP/2
- Low latency 
- Supports streaming 
- Language independent

#### What is an RPC? 
RPC stands for Remote Procedure Call. In client code it looks like you're just calling a function directly on a server


#### How to get started? 
- At the core of gRPC you need to define the messages and services using Protocol Buffers
- One .proto file works across 12 programming languages


Why Protocol Buffers?
- Language agnostic
- code can be generated for pretty much any language
- data is binary and efficiently serialized (small payloads)
- convenient for transporting a lot of data
