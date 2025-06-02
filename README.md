# ansible-roboshop
To run in the background 

nohup ansible-playbook -i inventory.ini -e ansible_user=ec2-user -e ansible_password=DevOps321 mongodb.yaml &>> /home/ec2-user/mongodb.log &
