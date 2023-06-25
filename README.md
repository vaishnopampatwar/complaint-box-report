# complaint-box-report

# Abstract

The "Complaint Box" is an application designed to enhance communication between citizens 
and municipal authorities. It provides a user-friendly platform for citizens to submit 
complaints related to various community issues such as road potholes, fallen trees, water 
pipeline leaks, drainage cleaning, and garbage problems. The application allows users to 
easily document and describe the issues, attach relevant images, and specify the location. 
Once a complaint is submitted, authorities can efficiently track, prioritize, and address the 
complaints, leading to more effective problem resolution. The "Complaint Box" application 
serves as a valuable tool for promoting citizen engagement, improving transparency, and 
fostering a collaborative approach to community development.

# Problem Statement

Android Application for Complaints towards Corporation

# Introduction

The "Complaint Box" is an innovative Android application developed to address the 
communication gap between citizens and municipal authorities. In many communities, 
citizens face challenges in effectively reporting various issues such as road potholes, fallen 
trees, water pipeline leaks, drainage cleaning, and garbage problems. Recognizing the 
importance of citizen engagement and efficient problem resolution, the "Complaint Box" 
application provides a user-friendly platform for citizens to submit complaints directly to the 
municipal authorities.
With the "Complaint Box" application, citizens can easily document and describe the issues 
they encounter in their community. They have the option to attach relevant images, providing 
visual evidence to support their complaints. Additionally, citizens can specify the precise 
location of the problem, ensuring accurate identification by the authorities. Once a complaint 
is submitted, the municipal authorities can efficiently track and prioritize the complaints, 
allowing for prompt action and resolution.
By utilizing the "Complaint Box" application, the communication between citizens and 
authorities is significantly improved. The application serves as a valuable tool that promotes 
citizen engagement, as it empowers individuals to actively participate in the betterment of 
their community. Furthermore, the transparency facilitated by the application fosters a 
collaborative approach to community development, allowing citizens and authorities to work 
together towards creating a cleaner, safer, and more livable environment.
The "Complaint Box" application offers a convenient and efficient means for citizens to 
report various community issues. It enhances the overall communication, transparency, and 
problem-solving capabilities between citizens and municipal authorities, leading to more 
effective resolutions and a stronger sense of community involvement.

#  Motivation

The motivation behind developing the "Complaint Box" application stems from the need 
to improve communication and problem-solving between citizens and municipal 
authorities. 
Several factors drive the development of this application:
- Enhancing Citizen Participation
- Efficient Problem Reporting
- Improved Transparency
- Targeted Problem Resolution
- Collaboration and Community Development

# Objectives

1) To study the existing complaint reporting systems and their limitations
2) To design and develop a user-friendly complaint box application.
3) To implement a feature such as estimate area of potholes, other municipal-related 
issues.
4) To analyse complaints using filters such as types of complaints


# Methodology

System Flow Diagram

![image](https://github.com/vaishnopampatwar/complaint-box-report/assets/83226115/ce6b1153-58d4-42ae-85cb-786db916efc5)

Admin Module

![image](https://github.com/vaishnopampatwar/complaint-box-report/assets/83226115/4aa405e4-57a7-4046-9cf2-7c51ace3cdfe)

Department Module

![image](https://github.com/vaishnopampatwar/complaint-box-report/assets/83226115/ce9586f7-a34d-481c-95eb-3d862b07de69)

# Use case Diagram:

![image](https://github.com/vaishnopampatwar/complaint-box-report/assets/83226115/87c9c4ec-cbf5-4fb3-a189-51a3b2eae18c)

# Implementation and Result

Citizen part Snapshots

![image](https://github.com/vaishnopampatwar/complaint-box-report/assets/83226115/418d56bc-8d9b-44dc-ae41-179e4c1a678e)

1) The first snapshot is the first page of the complaint box application, which includes three 
modules: Citizen, Admin, and Department.

![image](https://github.com/vaishnopampatwar/complaint-box-report/assets/83226115/9410078c-5eb6-4719-bd07-144f32b6edce)

2) The second snapshot describes the login page of the Citizen in the Complaint Box 
application.


![image](https://github.com/vaishnopampatwar/complaint-box-report/assets/83226115/607e6701-3ba0-49f1-9f5c-27ae0ca8d2ee)

If the citizen is a new user or has not registered yet, they are required to first register by 
entering their name, email, and password

![image](https://github.com/vaishnopampatwar/complaint-box-report/assets/83226115/6b7f4fe1-7816-46db-9709-802cb2b2f9f0)

After logging into the citizen module, the fourth snapshot shows the home page of the 
citizen side. It displays all the complaints that have been posted by all citizens.

![image](https://github.com/vaishnopampatwar/complaint-box-report/assets/83226115/9b998953-d00b-4714-9c97-9aba02fc34e9)

Citizens can post their complaints by clicking on the "add complaint" icon. They are 
required to select the type of complaint, enter the details such as title and description, and 
click on the picture icon to scan or take a photo of the issue. Upon clicking the picture, 
the location coordinates will be automatically fetched. If the complaint type is "pothole," 
it will estimate the area of the pothole. Finally, after clicking the "UPLOAD" button, the 
post will be uploaded

![image](https://github.com/vaishnopampatwar/complaint-box-report/assets/83226115/3995d90d-8dea-4fb4-9da7-1ff2aed0079e)

Citizens can view complaints by filtering them based on categories such as Pothole, 
Water issues, Dead Animals, Fire issues, Tax branches, and other complaints. The system 
initially displays the pothole type complaints.

![image](https://github.com/vaishnopampatwar/complaint-box-report/assets/83226115/66514cbd-44f9-43a3-9be6-a737bd4201ea)
Citizens can view water issues type complaints along with their location, status, and the 
person who posted the complaints. They also have the option to like the complaints and 
share them on social media platforms such as WhatsApp, Instagram, Facebook, and more.

Admin Part Snapshots:

![image](https://github.com/vaishnopampatwar/complaint-box-report/assets/83226115/c8c20505-52b6-4f72-bda1-42b3b6c070e7)

Once logged in, the admin can access and view all the complaints that have been posted 
by citizens. To streamline the complaint resolution process, the admin has the option to 
assign complaints to the respective department responsible for addressing them. This can 
be done by clicking on the "Assign To" button.The admin has the ability to view all 
complaints and can also access specific complaints with all the associated details

![image](https://github.com/vaishnopampatwar/complaint-box-report/assets/83226115/fde00066-dbfa-4a39-8d3b-c93fa76e8a81)

Upon logging into the admin section of the Complaint Box application, the admin has the 
ability to create and manage departments.

![image](https://github.com/vaishnopampatwar/complaint-box-report/assets/83226115/cd9b5f82-fd83-48f4-bff9-23e2c96b2756)

The third snapshot illustrates the process of adding a department by the admin.

![image](https://github.com/vaishnopampatwar/complaint-box-report/assets/83226115/da6815f3-0a84-4cd2-b865-25d706ef037f)

The admin can also view all complaints along with their status and generate a 
comprehensive report. The report includes information about the total number of 
complaints, pending complaints, completed complaints, and the percentage of completion 
for both pending and completed complaints.

Department Side Snapshots

![image](https://github.com/vaishnopampatwar/complaint-box-report/assets/83226115/ef0ccf02-888a-43be-9266-ddc600ef0e2d)

Department can see all complaints which are assigned by admin to that particular 
department.

![image](https://github.com/vaishnopampatwar/complaint-box-report/assets/83226115/a77e65ec-2c0f-4892-af45-de1bdfce260e)

Department will change the status of complaints from pending to completed with review
message.

# Conclusion

We concluding with this project, the Complaint Box application serves as an effective 
platform for citizens to report various complaints related to road problems and other issues to 
the corporation. The app aims to streamline the process of communication between citizens 
and the corporation, allowing citizens to easily and promptly inform about their concerns and 
complaints.
By providing a user-friendly interface and features such as attaching relevant images and 
specifying the location, the application enables citizens to accurately document and describe 
the problems they encounter. This ensures that the corporation receives detailed and 
actionable information to address the reported issues promptly.
The app promotes citizen participation and engagement in community development by 
empowering them to play an active role in identifying and resolving problems in their 
neighbourhoods. It facilitates a collaborative approach between citizens and the corporation, 
fostering a sense of ownership and responsibility for the maintenance and improvement of 
public infrastructure.

# References

1. Sunil Kumar Sharma and Rakesh Chandmal Sharma, Pothole Detection and Warning 
System for Indian Roads,” Advances in Interdisciplinary Engineering, 2019, pp. 511-
519, doi:10.1007/978-981-13-6577-5_48, Springer.
2. Lokeshwor Huidrom, Lalit Kumar Das and S.K. Sud, “Method for automated 
assessment of potholes, cracks and patches from road surface video clips,” 
conference of Transportation Research Group of India (CTRG), 2013, pp. 312-321, 
doi:10.1016/j.sbspro.2013.11.124, Elsevier.
3. Pothole Detection and Dimension Estimation System using Deep Learning (YOLO) and 
Image Processing: https://ieeexplore.ieee.org/document/9290547
4. Measuring size of objects in an image with OpenCV: 
https://pyimagesearch.com/2016/03/28/measuring-size-of-objects-in-an-image-with-opencv/
5. Apatti Mitra SMKC Application:
Apatti Mitra SMKC – Apps on Google Play
6. eMunicipality Application:
eMunicipality - Free download and software reviews - CNET Download
