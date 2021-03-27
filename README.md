# ObjectDetectionWebApp
<h4>How application works<h4>
<p>You need to add image with (.png,jpg,jpeg) format if you want to add image with any different format so you need to make some changes to the line 28 in Baggaeai/objdetection/views.py file. Then need to pass a xml file which contains the object details like(object name, and cordinates to locate object in the image, etc.) if you pass a wrong files then error will be shown.</p>
How to generate report?<br>
  click on generate report button ->pass the start date and end date. So that you get the report for that time period about Iamge and the object that is found inside image. 
  
<h4>Install require Libraries/Packages</h4>
->open terminal in project folder and run this command pip(if you mention version) install -r requirements.txt<br>
<h4>How to run Program file</h4>
open terminal in project folder and run this commands
-> python manage.py makemigrations<br>
-> python manage.py migrate<br>
-> python(if you mention version) manage.py runserver<br>


<h4>How web page looks?</h4>
![image](https://user-images.githubusercontent.com/47074753/112622502-2047be80-8e51-11eb-9835-e233b4e5bc83.png)

<h4> after passing image and xml file</h4>
![image](https://user-images.githubusercontent.com/47074753/112623520-7701c800-8e52-11eb-8361-9e5fa5eed2c7.png)
