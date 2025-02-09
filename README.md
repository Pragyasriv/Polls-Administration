Overview
This project is a Django-based Polls Administration System that allows users to create, manage, and vote on polls through an admin interface.

Features
User Authentication: Secure login/logout for administrators.
Poll Management: Create, update, and delete polls and choices.
Voting System: Users can vote on polls.
Results Display: View poll results in real time.

Installation
1. Clone the Repository
   git clone https://github.com/your-username/django-polls-admin.git
   cd django-polls-admin
2. Create a Virtual Environment
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
3. Install Dependencies
   pip install -r requirements.txt
4. Apply Migrations
   python manage.py migrate
5. Create a Superuser
   python manage.py createsuperuser
6. Run the Server
   python manage.py runserver

Usage
Navigate to the admin panel and create polls.
Add multiple choices to each poll.
Users can visit the polls page and cast their votes.
View real-time results of each poll.

Technologies Used
Django (Backend Framework)
SQLite/PostgreSQL (Database)
HTML/CSS (Frontend Styling)
