# Cloud Server Management Project
## Objective:
Demonstrate Linux fundamentals by:
1. Creating an AWS Ubuntu instance
2. Connecting via SSH using a PEM key
3. Performing package management (update, install, remove)
### 1. Creating AWS Ubuntu Instance
1. Logged into AWS Console
2. Navigated to EC2 > Instances > Launch Instance
3. Selected "Ubuntu Server 24.04 LTS"
4. Chose t2.micro instance type
5. Created new key pair named "First.pem"
6. Launched instance
![alt text](<Screenshot 2025-06-12 143222.png>)
![alt text](<Screenshot 2025-06-12 144649.png>)

### 2. Connecting to Instance
1. Located PEM key in Downloads folder:
  bash
   cd ~/Downloads
   ls -l cloud-server-key.pem

ssh -i "First.pem" ubuntu@ec2-34-277-162-7.compute-1.amazonaws.com

![alt text](<Screenshot 2025-06-12 153938.png>)

##### C. Package Management 
### 3. Package Management

#### Update Packages
sudo apt update
 ![alt text](<Screenshot 2025-06-12 154400.png>)

### 4. Install Tree Package
bash
sudo apt install tree -y
 ![alt text](<Screenshot 2025-06-12 154447.png>)
### 5.  # UPGRADE AND REMOVE TREE
sudo apt upgrade

sudo apt remove tree -y

 ![alt text](<Screenshot 2025-06-12 154733.png>)
### 5. 
 # INSTALLING NGINX
 ![alt text](<Screenshot 2025-06-12 154858.png>)

THANKS