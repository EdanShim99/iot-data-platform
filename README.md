## IoT Data Engineering Platform
Real time IoT platform with AWS, Kafka, Spark, and Terraform

# DOCUMENTATION
Made an EC2 instance of type t3.small with 20 GB gp3 SSD\
Key pair iot-platform-key.pem\ 
Security Group with inbound rules for ports 22 (SSH), 8080 (Airflow), 8081 (Kafka UI), and 9092 (Kafka)\ 
SSH Connection Setup, using the iot-platform-key.pm with ubuntu@EC2-PUBLIC-IP\
Set up Docker and Docker Compose\
Set up Kafka and created Topics for 4 different sensors\
Set up a Python Virtual Environment and a data generator script to generate data for 4 different sensors
