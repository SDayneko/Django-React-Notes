# Full-Stack Web Application with Django and React

This project is a full-stack web application that utilizes Django for the backend and React for the frontend. The application includes a note-taking feature and implements authentication using JWT tokens.

# Features

- **User Authentication**: Users can register, log in, and log out securely.
- **JWT Authentication**: Authentication is handled using JWT tokens.
- **Note Management**: Users can create, view, and delete notes.

## Technologies Used

- **Backend**: Django, Django REST framework
- **Frontend**: React, Axios
- **Authentication**: JWT tokens

## Setup Instructions

1. **Backend Setup**:

   ```bash
   python3 -m venv env
   source env/bin/activate
   pip install -r backend/requirements.txt
   cd backend
   python manage.py makemigrations
   python manage.py migrate
   python manage.py runserver
   ```

2. **Frontend Setup**:

- Run the following command to install the necessary dependencies:

  ```bash
    npm install
  ```

  -Start the React frontend using Vite:

      ```bash
      npm run dev
      ```

  -Create a production build of the application:

      ```bash
      npm run build
      ```

  -Preview the production build locally:

      ```bash
      npm run preview
      ```

## Usage

- **Register**: Users can register by providing a username and password.
- **Login**: Users can log in with their credentials to receive a JWT token.
- **Notes**: Logged-in users can create, view, and delete notes.

## Screenshots

1. **Home with Notes**:
   ![Home with Notes](/images/Home.png)

2. **Login**:
   ![Login](/images/Login.png)

3. **Register**:
   ![Register](/images/Register.png)

## License

This project is licensed under the MIT License.
