# YouWho
YouWho is an automated attendance system which works on video feed from the classroom. It is a modern face recognition web-application which uses Deep Learning to automatically detect all the faces in a given image and automatically identify the people therein. 
Our software would first require the input images of all the employees/students of the organization to train the model and fill up the dataset. Once this is done, whenever a person steps up to the camera installed, our software would automatically detect the name of the person and log their attendance in the backend, thus speeding up the whole attendance process.
<p>
	<img src="/User-Interface.png" width="700" />
</p>
How To Run ? 

	1. clone it on to your computer 
	2. make a separate python virtual environment or use the default one already installed on your machine
	3. Download this file
	4. put it inside \Attendance-System-Using-Face-Recognition\face_recognition_data directory
	5. run pip install -r requirements.txt inside \Attendance-System-Using-Face-Recognition directory
	6. Run python manage.py runserver inside \Attendance-System-Using-Face-Recognition directory to run the project
	7. by default the admin password should be set to 'echidna123' and the username is admin.
	8. the admin has been abled to change the password using the command:
	 		python manage.py changepassword admin

	-and Voila!
