# Deop-App-Service-MyApp

In this session we will create an application service,then deploy an application in it. 

1) Create an application service.

2) Choose an application.

3) Prepare the application.

4) Deploy the application.

5) Configure the application.

6) Test the application.

7) Monitor the application.

***Note: In order to +add slot your plan must be either standard or premium while configuring your web app. If you have selected basic plan during creation, no worries, here is how you can upgrade it!

![Screenshot 2023-03-08 at 6 30 11 PM](https://user-images.githubusercontent.com/121365233/223876456-e5b2af0a-2fca-48cd-b595-e6562a5e2320.png)

![Screenshot 2023-03-08 at 6 30 11 PM](https://user-images.githubusercontent.com/121365233/223876642-45a53787-31db-4d70-ae30-50d487a39956.png)

***Note: Additional slots can be created in case of updates or maintenance to avoid downtime. 

![Screenshot 2023-03-08 at 6 36 07 PM](https://user-images.githubusercontent.com/121365233/223877250-5b45b086-e470-499e-baba-e0858293df67.png)

4) To deploy the application first create a folder in your local. I have created "AppService" folder on my desktop. -open terminal in Visual Studio Code and open your created folder. 

![Screenshot 2023-03-08 at 6 44 07 PM](https://user-images.githubusercontent.com/121365233/223878268-05e6db1b-bc7c-4e26-98bb-91aae14f7d28.png)

***Make sure you have added all required extension in your VSCode (For in stance, "Azure App Service"). Make sure you have environment configuration file for your application. I have uploaded config file above. You can drag and drop it inside the created folder.

![Screenshot 2023-03-08 at 6 56 32 PM](https://user-images.githubusercontent.com/121365233/223879922-b26b0117-f0a0-4f96-a9a5-021ed860f6a2.png)

-- You can upload your app code or simply type it in terminal.

![Screenshot 2023-03-08 at 6 54 25 PM](https://user-images.githubusercontent.com/121365233/223879695-fd245365-4905-48e8-8f8c-db8ac4106a7b.png)

--To run app in local use "npm start" comment.

![Screenshot 2023-03-08 at 9 07 15 PM](https://user-images.githubusercontent.com/121365233/223897290-d4d9f42c-ea69-4788-8580-0043a434dd09.png)

--To create a production build, use "npm run build". Then go to Azure extension find your folder, click right and select "Deploy to web app..."

![Screenshot 2023-03-08 at 9 13 33 PM](https://user-images.githubusercontent.com/121365233/223898485-3457efb1-8879-4a09-8fd6-07acd9037055.png)

5) You can configure your application by additing codes.

6) To test deployed app click on "Browse Website" or you can find created app from the portal in overview section click domain name .

![Screenshot 2023-03-08 at 9 20 05 PM](https://user-images.githubusercontent.com/121365233/223899019-04da8d3e-7545-4492-979e-b1e67ca04b24.png)

![Screenshot 2023-03-08 at 9 22 50 PM](https://user-images.githubusercontent.com/121365233/223899673-edd7dde3-9c2f-4224-97a9-5b493533bab4.png)

![Screenshot 2023-03-08 at 9 22 04 PM](https://user-images.githubusercontent.com/121365233/223899698-c328506f-c7bc-4059-8e13-90e887029e7f.png)

***Additions and result of step 5

![Screenshot 2023-03-08 at 10 11 34 PM](https://user-images.githubusercontent.com/121365233/223907182-c1651eed-2c55-486f-8069-82456bca736a.png)

![Screenshot 2023-03-08 at 10 14 54 PM](https://user-images.githubusercontent.com/121365233/223907252-64504be5-8def-4d22-871e-1e40e63d5b17.png)


