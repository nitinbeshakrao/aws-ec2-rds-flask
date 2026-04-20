# Flask EC2 + RDS Project

## 📌 About Project

This is a simple Flask app running on AWS EC2 and connected to AWS RDS (MySQL database).

## 🛠️ Tech Used

* Python
* Flask
* AWS EC2
* AWS RDS
* PyMySQL

## 🚀 How to Run

### 1. Clone the project

git clone https://github.com/nitinbeshakrao/aws-ec2-rds-flask.git
cd app-python


### 2. Create virtual environment

python3 -m venv venv
source venv/bin/activate


### 3. Install dependencies

pip install flask pymysql

### 4. Run the application

python3 app.py




## 🌐 Open in browser

### Home Page

http://3.110.159.88:5000/


### DB Test

http://3.110.159.88:5000/test-db


## ⚙️ Important Setup

* EC2 security group: port 5000 open
* RDS security group: port 3306 open
* Flask code must have:

python id="r3"
app.run(host="0.0.0.0", port=5000)


## 🎯 Result

Flask app runs on EC2 and connects to RDS database successfully.
