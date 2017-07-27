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
    	- virtualenv "virtual-env-name-here"
##
		
#### 6. Activate the virtual environment:
    	- source "virtual-env-name-here"/bin/activate
##

#### 7. Install tipboard using pip:
		- pip install tipboard

#### 8. Confirm the installation: 	
		- tipboard runserver [<host>] [<port>]

#### 9. Point the web-browser to http://localhost:7272
		- you should see an empty dashboard

##
#### 10. To exit the enviroment use this command:
		- deactivate
