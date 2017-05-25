Instructions

1 - Create your application to be run (.sh .py .js etc)

2 - make it executable
	sudo chmod +x yourapp.sh

3 - Edit the Unit file template.service as needed

4 - Move the Unit file to lib subdirectory
	mv template.service /lib/systemd/system/your-unit-file.service

5 - Enable and start your service
	sudo systemctl enable your-unit-file.service
	sudo systemctl start your-unit-file.service

6 - Check if the service is running 
	sudo systemctl status your-unit-file.service



