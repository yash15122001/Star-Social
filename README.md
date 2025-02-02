
# Star Social - Django Application

Star Social is a social platform built with Django, where users can create and join groups, post blogs, view other groups, and perform various interactions. It comes with a user authentication system that allows users to sign up, log in, and log out. Admin panel is also available to manage the platform content.

## Features
- **User Authentication**: Users can log in, sign up, and log out.
- **Group Management**: Users can create groups, view existing groups, and join or leave them.
- **Blog Posting**: Users can create, edit, and delete blog posts.
- **Admin Panel**: Admins can manage users, groups, and blog posts via the Django Admin panel.
- **Responsive UI**: Built with HTML, CSS, Bootstrap, and JavaScript for a responsive and user-friendly interface.

## Technologies Used
- **Django**: Web framework for building the application.
- **HTML/CSS/Bootstrap**: Frontend technologies for designing the user interface.
- **JavaScript**: Used for interactivity and dynamic content.
- **SQLite**: Database for storing user data, groups, and blog posts (you can configure a different database if required).

## Installation

### Prerequisites
- Python 3.x
- Django 3.x (or higher)
- pip (Python package manager)

### Clone the Repository
```bash
git clone https://github.com/your-username/star-social.git
cd star-social
```

### Set up a Virtual Environment (Optional but Recommended)
```bash
python3 -m venv venv
source venv/bin/activate   # On Windows use 'venv\Scriptsctivate'
```

### Install Dependencies
Install the necessary dependencies using `pip`.

### Database Migration
Run the migrations to set up the database:
```bash
python manage.py migrate
```

### Create a Superuser (Admin)
To access the Django Admin panel, create a superuser:
```bash
python manage.py createsuperuser
```
Follow the prompts to create a superuser.

## Running the Application

To run the application locally, use the following command:
```bash
python manage.py runserver
```

The application will be accessible at `http://127.0.0.1:8000/` in your browser.


## Usage

1. **User Registration and Login**
   - Navigate to `/signup/` to create a new account.
   - After registering, log in at `/login/`.

2. **Managing Groups**
   - Users can create a group from the groups page.
   - Users can view existing groups and join or leave them.
   
3. **Posting Blogs**
   - Users can create, update, or delete blog posts in their profile.

4. **Admin Panel**
   - Visit `/admin/` to access the admin panel.
   - Login with the superuser credentials to manage users, groups, and posts.

