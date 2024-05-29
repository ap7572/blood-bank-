# blood-bankmanagement-system
# Information Management System For A Blood Bank

Install Dependencies:
```
 pip install -r requirements.txt
```
Start the server:
```
export FLASK_APP='app.py'
```
Run the app:
```
flask run
```
## Database commands
### Open MySQL in terminal:
```
mysql -u root -p
```
If the above commands doesn't works then:
```
sudo mysql -u root -p
```
followed by updating the password using:
```
$ ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'new-password';
```
Once this is done stop and start the mysql server:
```
$  sudo service mysql stop
$  sudo service mysql start
```
### View all databases:
```
SHOW DATABASES;
```
Creating a new database:
```
CREATE DATABASE bloodbank;
```
Use any database:
```
USE bloodbank;
```

## Snapshots
### Home Page
![](snapshots/home.png)
### Contact Us
![](snapshots/contact.png)
### Register
![](snapshots/register.png)
### Login
![](snapshots/login.png)
### Dashboard
![](snapshots/dashboard.png)
### Add Donor
![](snapshots/donate.png)
### Donor Logs
![](snapshots/logs.png)
### Donor Blood Details
![](snapshots/details.png)
### Blood Requests
![](snapshots/requests.png)
