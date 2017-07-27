## Installing tipboard on AWS instance:
#
#### 1. Connect to AWS instance
##

#### 2. Install virtual environment:
		- sudo apt-get install python-virtualenv
##

#### 3. Install redis-server:
		- sudo apt-get install redis-server
##		
		
#### 4. Install python development pachake:
    	- sudo apt-get install python-dev
##
				
#### 5. Create a new virtual environment:
    	- virtualenv <name_of_virtual-env>
##
		
#### 6. Activate the virtual environment:
    	- source <name_of_virtual-env>/bin/activate
##

#### 7. Install tipboard using pip:
		- pip install tipboard
##

#### 8. Confirm the installation: 	
		- tipboard runserver [<host>] [<port>]
##

#### 9. Create a new tipboard project:
		- tipboard create_project <name_of_project>
##

#### 10. Confirm the installation: 	
		- tipboard runserver 0.0.0.0 7272
##		
		
#### 11. Point the web-browser to AWS_Public_ip:7272
		- you should see an empty dashboard
##

#### 12. To exit the enviroment use this command:
		- deactivate
