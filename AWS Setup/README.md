	-1. In AWS Dashboard create an Ubuntu Instance.

	-2. Default username is "ubuntu". 

	-3. Select the instance hardwares.

	-4. Create a ssh key (default *.pem).

	-5. Download the key.

	-6. Install putty on your machine
		- sudo apt-get install putty & putty-tools

	-7. Copy the public IP of your instance or DNS entry

	-8. Set the permission on the key to 400.

	-9. Connect to your instance using the following command
		- ssh -i /path/to-key ubuntu@IP

