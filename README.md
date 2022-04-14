# HR-ONHAND

This repo is the parent repo which will be consist of all other micro-services that connects via Kafka. Right now Authentication service has already been implemented and authorization service is on the way. There will be two more services as tracking and payment. All those services are going to run inside the same Docker network and connect each other via Kafka publish/consume.