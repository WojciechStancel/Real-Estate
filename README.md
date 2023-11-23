# WS Real Estate  <img width="30px" src="https://github.com/WojciechStancel/Real-Estate/assets/121879383/4571602e-8f76-4306-b434-b4b18529fecf"> 


Welcome to the WS Real Estate Agency web application. This application is built using Django for the backend and Bootstrap for the frontend. It serves as a platform for managing real estate listings, allowing users to browse and add property listings, as well as providing authentication and registration features. The application utilizes a PostgreSQL database, and it is hosted on AWS with Nginx as the web server.

<img width="100%" alt="ws_real_estate_scr" src="https://github.com/WojciechStancel/Real-Estate/assets/121879383/e7a5d065-45f7-4fe7-b2b6-c42be2dfb4df">


## Features <img width="20px" src="https://github.com/WojciechStancel/Real-Estate/assets/121879383/cad7a0b4-a0f1-40d2-a072-779a7c4f4583">


- **Property Listings:** Browse and search for available real estate listings.
- **User Authentication:** Register and log in securely to access additional features.
- **Listing Management:** Registered users can add and manage their property listings.
- **Admin Panel:** Administrators can manage users, listings, and website content.
- **Database:** The application uses PostgreSQL for data storage, ensuring data integrity and security.
- **Hosting:** The application is hosted on AWS, making it accessible online.

## Technology Stack <img width="20px" src="https://github.com/WojciechStancel/Real-Estate/assets/121879383/95ae4ffc-3260-40f2-9908-45801ebfe96b">


- Backend: Django
- Frontend: Bootstrap
- Database: PostgreSQL
- Web Server: Nginx
- Hosting: Amazon Web Service

## Installation <img width="20px" src="https://github.com/WojciechStancel/Real-Estate/assets/121879383/b2b4ed26-93aa-426b-a3a0-a984d3c55ce7">


To set up this application locally, follow these steps:

1. Clone this repository: `git clone https://github.com/WojciechStancel/Real-Estate.git`
2. Navigate to the project directory: `cd RealEstate`
3. Install Python dependencies: `pip install -r requirements.txt`
4. Check the `.env.template` - You need to create your own `.env` in the root of project with `SECRET_KEY` to run app. If you want to make an inqury you have to create `EMAIL_HOST_USER` and `EMAIL_HOST_PASSWORD`, other KEYS are optional - they were used to deployment.
5. If you don't want to create `.env` file, just change the mentioned variables above to your own data, but for security reasons **do not push this variables on github**.
6. IN `settings.py` you have installed simple sqlite3 database, so you can use application without problems on your local machine.
7. Makemigrations: `python manage.py makemigrations`
8. Run database migrations: `python manage.py migrate`
9. Start the Django development server: `python manage.py runserver`

For a production deployment, you will need to configure Nginx and gunicorn to serve the application.

## Usage <img width="20px" src="https://github.com/WojciechStancel/Real-Estate/assets/121879383/6f936693-602b-4ead-9183-ce2a66dc1839">


- Visit the application at http://51.20.211.102/
- Register an account or log in to access advanced features.

## Acknowledgments <img width="20px" src="https://github.com/WojciechStancel/Real-Estate/assets/121879383/2c32b61f-cc0c-480e-9613-47e853ad349a">


I would like to acknowledge Brad Traversy (https://github.com/bradtraversy) for the tools and resources that made this project during Python Django Dev to Deployment Course. It was a big pleasure to learn new stuff. 

Link to course: https://www.udemy.com/course/python-django-dev-to-deployment/

---

> My Website 💻 [CodeCr8ive.pl](https://www.codecr8ive.pl) &nbsp;&middot;&nbsp;
> Checkout my GitHub account
[Github <img width="20px" src="https://github.com/WojciechStancel/Notes-React-App/assets/121879383/fc63de6c-91ae-4eb7-ac97-a5a365bdf073)">](https://github.com/WojciechStancel) &nbsp;&middot;&nbsp;
> Do not hesitate to contact me on
 [Linkedin <img width="20px" src="https://github.com/WojciechStancel/Notes-React-App/assets/121879383/94d42b30-025f-4997-9ff5-9491c49d9026">](https://www.linkedin.com/in/wojciech-stancel/) 

