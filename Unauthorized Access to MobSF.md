Vulnerability Type:
Unauthorized Access to MobSF
Exploitation Method:
Access the MobSF interface deployed on a system. Append "/recent_scans/" to the URL after the homepage to view a list of applications. From there, one can access APK or IPA reports as needed, potentially exploiting vulnerabilities that could lead to sensitive information disclosure.
Solution:
It is recommended to implement access restrictions.
Version: MobSF v3.7.8 Beta or earlier


Example 1:
Test URL: https://3.137.91.62/
version：MobSF v3.7.8 Beta
Access the MobSF interface that has been deployed.
![image](https://github.com/woshinibaba222/hack16/assets/55568679/ead612ca-5f49-4843-bad7-4187218d59c3)
Click on the area indicated in the image to access the API documentation.
![image](https://github.com/woshinibaba222/hack16/assets/55568679/38432be0-c93a-4402-ba91-368b76f46462)
Click on "RECENT SCANS."
![image](https://github.com/woshinibaba222/hack16/assets/55568679/30cf8b20-5ed7-4e79-9908-a2f24fa89203)
You can find reports of uploaded mobile applications, and you can determine whether they are IPA or APK files.
![image](https://github.com/woshinibaba222/hack16/assets/55568679/45acd8ad-031b-4a37-b3e1-718da2c0d1f5)
Click on "Static Report" to view detailed information about the mobile application.
![image](https://github.com/woshinibaba222/hack16/assets/55568679/6e621f89-ae7e-41b4-82ff-88a3d7ea5dc4)
You can click the "Download" button to download the installation package as well.
![image](https://github.com/woshinibaba222/hack16/assets/55568679/df1b077e-e6f7-4cf1-a75b-0eab2de6b99e)
You can also view the scan PDF report online, which may reveal sensitive information such as IP addresses and addresses.
![image](https://github.com/woshinibaba222/hack16/assets/55568679/1b640612-d411-4fa9-8c7a-326c34117084)
![image](https://github.com/woshinibaba222/hack16/assets/55568679/244a9434-9152-47dc-a186-459a85b905d0)
Example 2:
Test URL: http://34.235.105.166:8001/
Version: MobSF v3.4.5 Beta
![image](https://github.com/woshinibaba222/hack16/assets/55568679/c17ec797-274b-4fec-bdca-d5a3c867acb2)
Click on "SCANSDYNAMIC" on the homepage.
![image](https://github.com/woshinibaba222/hack16/assets/55568679/2278d89d-5f4c-4c96-8d9b-c298c2018c38)
Next, click on "Recent Scans."
![image](https://github.com/woshinibaba222/hack16/assets/55568679/f0d425e5-c5d6-41d1-bbcc-a11383a9c4c0)
Click on "Static Report." You will be able to access the detailed information page, and you can also download the APK of the application.
![image](https://github.com/woshinibaba222/hack16/assets/55568679/452798d4-ce0f-47bd-b1ae-6136be9eb59f)
![image](https://github.com/woshinibaba222/hack16/assets/55568679/d016fd1c-8f84-4f3e-8d98-3d8e01ff99e2)
You can continue to view email and IP information.
![image](https://github.com/woshinibaba222/hack16/assets/55568679/beaf304c-daab-4f31-9b9d-b7a9dd84b5a7)
![image](https://github.com/woshinibaba222/hack16/assets/55568679/c44d2b48-437b-4dfc-8df5-a50ac02c30fe)
Example 3:
Test URL: http://167.71.229.12:8080/
Version: MobSF v3.7.4 Beta
![image](https://github.com/woshinibaba222/hack16/assets/55568679/c12888c4-36b8-4a7e-bf78-c7eeefbd9a25)
You can directly view the list of apps by appending "/recent_scans/" to the URL.
![image](https://github.com/woshinibaba222/hack16/assets/55568679/ef523110-7c94-40ab-932e-bf11fad9ab5c)
Example 4:
Test URL: http://173.212.247.212:8002/
Version: MobSF v3.6.6 Beta
You can directly access http://ip:port/recent_scans/ to view the app list.
![image](https://github.com/woshinibaba222/hack16/assets/55568679/4e2efe8d-e006-4f07-a05a-d93630c06e7d)
![image](https://github.com/woshinibaba222/hack16/assets/55568679/406fd0aa-f38e-49f3-ad68-53ad37f626a8)
You can enter the report to view sensitive information.
![image](https://github.com/woshinibaba222/hack16/assets/55568679/14e7a526-c625-46ac-883c-0c03c414bf0e)
![image](https://github.com/woshinibaba222/hack16/assets/55568679/1fa94aa2-702a-44fc-ba7c-9cd0b3861b0d)




