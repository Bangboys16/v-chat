
Vigi Chat is a simple chat application built using Django. This application allows users to create and join chat rooms where they can communicate in real-time. The application includes two main views: the lobby and the chat room.

Features
Lobby: A central hub where users can see a list of available chat rooms and join one.
Room: The actual chat interface where users can send and receive messages in real-time.
Screenshots
Include screenshots of your lobby and room pages here.

Requirements
Python 3.x
Django 3.x or later

Installation
Clone the repository:
git clone https://github.com/yourusername/vigi-chat.git
cd vigi-chat

Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

Install the required dependencies:
pip install -r requirements.txt

Run database migrations:
python manage.py migrate

Create a superuser to access the Django admin:
python manage.py createsuperuser

Start the development server:
python manage.py runserver
Open your browser and navigate to http://127.0.0.1:8000/ to access Vigi Chat.

Project Structure
vchat/: Main Django app for Vigi Chat.
views.py: Contains the views for the lobby and chat rooms.
templates/: Contains the HTML templates for the lobby and room.
lobby.html: Template for the lobby view.
room.html: Template for the chat room view.
Usage
Lobby: When you visit the main page, you'll see the lobby where you can join existing chat rooms or create a new one.
Room: After joining a room, you'll be redirected to the chat interface where you can start chatting in real-time.
Contributing
Fork the repository.
Create a new branch: git checkout -b feature-name.
Make your changes and commit them: git commit -m 'Add some feature'.
Push to the branch: git push origin feature-name.
Submit a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
If you have any questions, feel free to reach out at [edidiongeka54@gmail.com].

