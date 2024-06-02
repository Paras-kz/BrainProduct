#Description --
This Django project, named Candidate Assessment, is a simple web application designed to manage products and orders through a RESTful API. It provides endpoints for CRUD operations on products and orders, along with authentication and authorization mechanisms.

#Steps to setup --

-Cloning git repo:
git clone https://github.com/your-username/CandidateAssessment.git

-Navigate to the project directory:
cd CandidateAssessment

-Create and activate a virtual environment:
python -m venv venv

-Activate Venv:
venv\Scripts\activate

-Install project dependencies:
pip install -r requirements.txt

-Apply migrations:
python manage.py migrate

-Create a superuser for accessing the admin interface:
python manage.py createsuperuser

-Start the development server:
python manage.py runserver

--Usage--
Access the Django admin interface at http://127.0.0.1:8000/admin/ to manage products and orders.

Authentication is required for accessing the API. Obtain JWT tokens by logging in through the token endpoint(POST): http://127.0.0.1:8000/api/token/

Use the provided RESTful API endpoints for CRUD operations on products and orders:
Products: http://127.0.0.1:8000/api/products/
Orders: http://127.0.0.1:8000/api/orders/

API Documentation
Swagger documentation: http://127.0.0.1:8000/swagger/