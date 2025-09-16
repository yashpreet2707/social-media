# Social Media Platform 


Welcome to the Social Media Platform project built using Django! This project aims to create a basic social media platform where users can register, log in, post updates, connect with friends, and more. The platform provides a foundation that you can extend and customize to create your own unique social media experience.


## Features

- User registration and authentication
- User profiles with profile pictures and bio
- News feed displaying posts from friends
- Post creation and deletion
- Like  on posts
- Follow to a user & see its post on home feed
- unfollow to a user
- User search functionality
- Responsive and user-friendly design

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Ayushsav/social-media.git
   ```

2. Navigate to the project directory:

   ```bash
   cd social-media
   ```

3. Create a virtual environment:

   ```bash
   virtualenv venv
   ```

4. Activate the virtual environment:

     ```bash
     source venv/bin/activate
     ```

5. Install the project dependencies:

   ```bash
   pip install django
   pip install pillow

   ```

6. Perform database migrations:

   ```bash
   python manage.py migrate
   ```

7. Create a superuser account for administrative access:

   ```bash
   python manage.py createsuperuser
   ```

8. Run the development server:

   ```bash
   python manage.py runserver
   ```

9. Access the application in your web browser at `localhost:8000/`.
