# docker-httpd-containerimage-launch-webserver-ansible  

🔰 Writing an Ansible PlayBook that does the following operations in the managed nodes:  
🔹 Configure Docker  
🔹 Start and enable Docker services  
🔹 Pull the httpd server image from the Docker Hub  
🔹 Run the docker container and expose it to the public  
🔹 Copy the html code in /var/www/html directory and start the web server  
🔹 Note : In this case I am considering that every Target Node has yum pre configired.  
🔹 Result : Httpd server launched on the top of Docker Engine by Automation with help of Ansible.
