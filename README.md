# mantaflo
A framework for totally stateless workflows

There is a huge demand for workflow engine technologies out there. jBPM and BPMN are getting pretty old, and a lot of folks in the enterprise are looking for a newer solution that takes advantage of today's no sql storage options. Or, can we develop a workflow engine that leverages topics/queues instead of a database for operations? That is what mantaflo is. It's essentially a workflow engine that doesn't need a database operationally, but can store process data in a storage solution of choice for viewing. I also wanted this project to meet other requirements, like being reactive, ultra scalable, and easy to onboard new use cases, and of course, friendly in an enterprise environment. This project would be the centerpiece of an intelligent automation platform, and is in general, a next step forward in enterprise automation.

Manta apps communicate through a broker of your choice, such as kafka, rabbitmq, sqs, or kinesis. This capability is easily extendable and configurable.
