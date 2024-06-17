# protobuf
ITS-FMS Interface protub definition

The ITS-FMS Interface is defined as an standard for communication between logistic IT-suppliers (FMS) wanting to integrate Intelligent Transport Systemsservices and ITS cloud service providers (CSP) that offer the required services. These services consist of usefull real time traffic and infrastucture events that are relevant on the current route of the truck.

This repository contains the protobuf definition used to genereate classes with protoc for your code to serialize and deserialize protobuf messages.

For protoc: https://github.com/protocolbuffers/protobuf/releases
used command: protoc --java_out=java FMS_ITS_Interface_Specification.proto

For more information about protobuf: https://protobuf.dev/overview/