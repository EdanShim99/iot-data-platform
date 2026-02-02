## IoT Data Engineering Platform
Real time IoT platform with AWS, Kafka, Spark, and Terraform

# DOCUMENTATION
Made an EC2 instance of type t3.small with 20 GB gp3 SSD<br/>
Key pair iot-platform-key.pem<br/>
Security Group with inbound rules for ports 22 (SSH), 8080 (Airflow), 8081 (Kafka UI), and 9092 (Kafka)<br/>
SSH Connection Setup, using the iot-platform-key.pm with ubuntu@EC2-PUBLIC-IP<br/>
Set up Docker and Docker Compose<br/>
Set up Kafka and created Topics for 4 different sensors<br/>
Set up a Python Virtual Environment and a data generator script to generate data for 4 different sensors
