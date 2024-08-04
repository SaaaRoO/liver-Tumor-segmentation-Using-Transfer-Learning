
•	Deep Learning Model: The core of the project was the deep learning model,which integrated transfer learning with ResNet50 and the U-Net architecture.
This combination enabled the model to achieve impressive accuracy levels, reaching 99.01% in training and 98.9% in testing phase.

•	Flask Web Application: The project utilized Flask, a lightweight web framework for Python, to deploy the machine learning model as a web application.
Flask provided the infrastructure necessary to handle HTTP requests and responses, facilitating the integration of the model with the web interface.

•	HTML/CSS/JS Frontend: The frontend of the web application was developed using HTML, CSS, and JavaScript.
These technologies were employed to create an intuitive and user-friendly interface for uploading CT scan images and displaying the segmentation results.

Functionality: 
•	Image Upload: Users can upload CT scan images of liver scans through the web interface. 
•	Segmentation: The uploaded images are processed by the machine learning model, which performs segmentation to identify and delineate liver tumors. 
•	Result Display: The segmentation results, including the presence of tumors and corresponding mask images, are displayed to the user in real-time. 

.  Result of Resnet50: 
 - Training result:
![image](https://github.com/user-attachments/assets/e807d765-813e-4063-981a-68891f6aca77)

 - Plotting after training:
![image](https://github.com/user-attachments/assets/7fd65d70-8496-413f-ab29-3862a5cf5ba9)

 - Validation Accuracy:
![image](https://github.com/user-attachments/assets/9fd6290a-580b-42c8-ba9c-a1626bd9998d)

- Testing Accuracy;
  ![image](https://github.com/user-attachments/assets/601a0ee8-5924-49fd-8bb4-d10889502d19)
  - Prediction Function of Resnet50:
    ![image](https://github.com/user-attachments/assets/fd6cfa9b-5886-461e-9054-23567124e627)

  . Result of U-NET:
  - Training Accuracy :
 ![image](https://github.com/user-attachments/assets/17b39482-ee16-47ce-8e1f-f530c818eb66)

- Validation Accuracy:
  ![image](https://github.com/user-attachments/assets/dbdb9c54-07bd-43a1-9398-ab2c64d832fb)

 -  Prediction Function of U-NET:
   ![image](https://github.com/user-attachments/assets/00eebcfb-8ad2-463a-a9cb-dd5261f181a8)

. MODEL SUMMERY WITH DETAILS: 
![image](https://github.com/user-attachments/assets/8a5b9a70-1bae-4bdd-a1d2-66262cc757ff)

![image](https://github.com/user-attachments/assets/6f7d69e4-df5f-4b0a-81ce-6e19d6a6f02c)

- Test cases: 
. Test case 1 <<< CT scan of a healthy, unaffected liver

  ![image](https://github.com/user-attachments/assets/08180f36-5a33-44cf-9379-f70274c60868)

  ![image](https://github.com/user-attachments/assets/2dff3dc6-56b2-4e94-a3c6-9ca2b2422b58)

 - Test case 2 << CT scan for liver with tumor :  

![image](https://github.com/user-attachments/assets/062ad087-8d01-4ba9-a13b-12d36f983204)

![image](https://github.com/user-attachments/assets/19872a92-7b65-46e8-8da8-b90096527d1f)



. Design of the website: 
![image](https://github.com/user-attachments/assets/ac89a028-059a-417f-9e88-ddd5a7196312)

![image](https://github.com/user-attachments/assets/df2ed4d8-372a-4f30-b25f-3c3bf3f4ea17)

![image](https://github.com/user-attachments/assets/089f9344-f228-4d66-9e4d-8f7c1055dc40)




    



