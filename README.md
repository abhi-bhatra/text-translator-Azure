# Text Translator App
Creating a web application with artificial intelligence (AI) doesn't need to involve a lot of code or creating services from scratch. Let's imagine we wanted to create a website that can translate text for the user.

For the front end, we want something that will allow us to integrate our services without having to jump through a lot of hoops. A framework like Flask is a perfect choice. Flask is described by its creators as a "micro-framework", meaning it provides the core services required, such as routing and templating, but otherwise allows you to use whatever backend services your application needs. It's also lightweight, making it quick to set up and deploy. We don't need a database or anything fancy. We just need a framework to create our UI, and be able to call the back-end service.

<img width="710" alt="image" src="https://user-images.githubusercontent.com/63901956/169641670-f911dfc9-2c47-4a0c-b895-083165c9e422.png">

### Steps
- Create a Flask application
- Create a Translator service on Azure
- Use requests to call the service

### WebApp Flow

**Setup your environment**
Install the necessary tooling, create the folder for their project, and setup the necessary Python libraries.

**Directory Tree**

<img width="196" alt="image" src="https://user-images.githubusercontent.com/63901956/181758283-65e0d018-107f-4f37-8610-8f5509cc7507.png">


**Create the app**
After setting up the environment, create the template for the landing page and test that application is running correctly.

**Create the Translator service**
Once the project is up and running, create the necessary services on Azure. Obtain the keys to call the service, and properly store them in a .env file.

**Call the service from the app**
Add the code to call the Translator service. Test the application and seeing text translated in their app!

<img width="708" alt="image" src="https://user-images.githubusercontent.com/63901956/169641842-7186916c-2648-440e-84b4-6fd6ec7d9192.png">

Access the application at: https://texttransalator.azurewebsites.net/

**Link might not work due to collapse of Azure subscription, but you can clone this repository and host the application on your Azure subscription to make it work**
