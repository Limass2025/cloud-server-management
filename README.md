# cloud-server-management
AWS FIRST INSTANCE
Step 1: Set Up Your Environment
For Windows Users:
Download and install MobaXterm

Step 2: Connect to Your Cloud Server
Locate your PEM key:

Typically downloaded to your Downloads folder

Open your terminal and navigate to the Downloads folder:

bash
cd ~/Downloads
List files to verify your PEM key:

bash
ls -l

Get your server's public IP from AWS console

Connect via SSH:

bash
ssh -i "ubuntu.pem" ubuntu@your-public-ip
Replace "ubuntu.pem" with your actual key filename

Replace "your-public-ip" with your server's IP

Accept the security prompt by typing "yes"

Step 3: Package Management
1. Update package lists
bash
sudo apt update

2. Install the 'tree' package
bash
sudo apt install tree

3. Verify installation
bash
tree ~/Downloads

4. Remove the 'tree' package
bash
sudo apt remove tree

Step 4: Additional Practice
Install Nginx web server:

bash
sudo apt install nginx

# CREATING AWS UBUNTU INSTANCE
![alt text](<Screenshot 2025-06-12 143222.png>)

# CONNECTING AND STARTING THE INSTANCE ON AWS

![alt text](<Screenshot 2025-06-12 144649.png>)

# CONNECTING TO THE INSTANCE THORUGH MOBAXTERM
![alt text](<Screenshot 2025-06-12 153938.png>)

# UPDATE USING UPDATE
 ![alt text](<Screenshot 2025-06-12 154400.png>)

 # INSTALLING TREE
 ![alt text](<Screenshot 2025-06-12 154447.png>)

 # UPGRADE AND REMOVE TREE
 ![alt text](<Screenshot 2025-06-12 154733.png>)

 # INSTALLING NGINX
 ![alt text](<Screenshot 2025-06-12 154858.png>)

THANKS