# How to run this project on your system

First clone the project and extract the files on your system.

Then open powershell on the same folder and run the command  ( pip install -r req.txt  )

Be sure that the  libraries::

asgiref==3.3.1,

click==7.1.2,

cmake==3.18.4.post1,

Django==3.1.3,

dlib==19.21.0,

face-recognition==1.3.0,

face-recognition-models==0.3.0,

numpy==1.19.3,

opencv-python==4.4.0.46,

Pillow==8.0.1,

playsound==1.2.2,

pytz==2020.4,

sqlparse==0.4.1   are properly installed.

After that open project on vs code and in new terminal run the command  ( python manage.py runserver  ). Make sure that you are in the same directory othervise no such file or directory present error will show. For this you can run the command- cd face_recognition_attendance_system-dev 

The id and password for admin login is (id=arun) and (password=arun), however you can change it by running the command ( python manage.py createsuperuser  )

![Screenshot (314)](https://user-images.githubusercontent.com/98249951/170855597-2eaf00c8-4029-4017-a5e0-2d4617520388.png)

![Screenshot (315)](https://user-images.githubusercontent.com/98249951/170855598-811a6af1-9ade-46a1-95f6-8e1b38acdc2c.png)

![Screenshot (316)](https://user-images.githubusercontent.com/98249951/170855601-f9ab1748-0300-4c11-bbf9-607e1459c1fd.png)
