# Assignment of Scalable Services
# Online Book Service

# About Project
The main objective of Online Books service has three autonomous services such as order, inventory and payment service. Each service is independently deployable and has separate databases. Database that has been used is PostgreSQL. Ordering service is responsible for placing the order. It calls payment service, generates the payment id, updates order database and publishes updated order details to Kafka. Each time an order is placed stock gets updated in inventory service by using Kafka asynchronously. Payment Service handles bill payments that can be done by using Debit/Credit card or by Cash. Docker container is used to deploy all the services. Each service has a separate Docker image.

Technologies and dependencies:
Java, PostgreSQL, Kafka, Zookeeper, Docker


# Individual Contributions
»	Sreedevi Chittoor – 2020mt93105 - Design, Development, Documentation <br />
»	Amanpreet Singh – 2020mt93115 - Design, Development, Docker Deployment, Video Making <br />
»	Neeraj Chaudhary – 2020mt93056 - Design, Development, Video Making, Documentation <br />
»	Pushpal Chatterjee – 2020mt93216 - Design, Development, Docker Deployment <br />




