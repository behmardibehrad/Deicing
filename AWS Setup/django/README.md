## Installing Django on AWS instance:
#
#### 1. Connect to AWS instance
##

#### 2. Install virtual environment:
		- sudo apt-get install python-virtualenv
##

#### 3. Install python development pachake:
    	- sudo apt-get install python-dev
##
				
#### 4. Create a new virtual environment:
    	- virtualenv <name_of_virtual-env>
##
		
#### 5. Activate the virtual environment:
    	- source <name_of_virtual-env>/bin/activate
##

#### 6. Install Django using pip:
		- sudo pip install django
##

#### 7. Confirm the installation: 	
		- python -m django --version
		- or
		- >>> import django
		- >>> print(django.get_version())
		- 1.11.3

