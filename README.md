FACE RECOGNITION BASED ATTENDANCE SYSTEM.

Generally, recording the attendance of the employee or student is one of the key process in any organisation. There are some traditional methods of recording attendance such as -> ✔In schools and colleges,attendance is taken by teachers manually at the beginning and ending of the class. ✔ Employees signing an attendance register when they report for duty.In some organisations,the attendance signing is done twice a day,once in the morning and then after the leaving of the organisation. ✔ Supervisor physically verifies employees and mark the attendance. ✔Fingerprint Readers are used for recording attendance. 

The problem:

 With the manually taking attendance is that it requires some time to take and also the manual process will have chances to make mistakes in most of the cases.

With the Fingerprint Readers is that:
    - Not suitable with wet hands.
    - Germs Transmit.
    - Can't use it if the person doesn't have fingers .
## Screenshots

![Flow Chart] (https://drive.google.com/file/d/1dz1GwIl6QHOJ8ISiBm4u0b__4IJSQDn6/view?usp=sharing)
## Libraries:
Numpy-
      pip install numpy
Matplotlib-
      pip install Matplotlib
OpenCV-
      pip install opencv-python
Face Recognition-
     pip install face-Recognition
Pillow Library-
     pip install Pillow
                    
## Module:

1.REFERENCE DATABASE:
                 When Employees are recruited and join duty as a new employee,the company records the following and store them in reference  database.
                   Name of the Employee(First Name, Last Name),Gender,Age,Qualifications,Address,Experience,Photo and so on .
2. ATTENDANCE REPORTING:
                 The employees are required to report in front of a camera and present their face. Proper lighting must be provided.The camera must be placed in such a way that        the employees can post with camera at the eye level.
3. ATTENDANCE RECORDING:
                 When the employee presents in front of the camera, the face image is captured, compared with the database image, recognized and the attendance 
   is recorded with time stamp in a datafile.
4. ATTENDANCE RECORDING CONFIRMATION: 
                 To give a better user experience, the successful recording is announced to the user as follows:
                 1. Display: Display the image captured with caption of the employee name. If the face cannot be recognized, the text Unable to recognize face is given in the                         caption.
                 2. Audio: Announce the name of the employee and say : Attendance recorded Successfully. If the Face Cannot be recognized and employ identified,
                  announce "Unable to Recognize Face.
                  