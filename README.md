# Instructions

## Prerequisites

Before you begin, ensure that you have the following installed on your system. If you don't have the same version, I recommend using nvm for Node.js and pyenv for Python to manage different versions.

-   Python (version 3.12.1)
-   Node.js (version 20.11.1)
-   Git

## Step 1: Clone the Repository

1. Open your terminal or command prompt.
2. Change to the directory where you want to create your project.
3. Run the following command to clone the repository:
    ```
    git clone https://github.com/DeylerAF/django-react-ecommerce.git
    ```

## Step 2: Set Up the Backend (Django)

1. Change to the project's backend directory:
    ```
    cd django-react-ecommerce/app/backend
    ```
2. Create a virtual environment:
    ```
    python -m venv .venv
    ```
3. Activate the virtual environment:
    - On Windows:
        ```
        .venv\Scripts\activate
        ```
    - On macOS and Linux:
        ```
        source .venv/bin/activate
        ```
4. Install the required Python packages:
    ```
    pip install -r requirements.txt
    ```
5. Run the database migrations:
    ```
    python manage.py migrate
    ```

## Step 3: Set Up the Frontend (React)

1. Change to the project's frontend directory:
    ```
    cd django-react-ecommerce/app/frontend
    ```
2. Install the required Node.js packages:
    ```
    npm install
    ```

## Step 4: Start the Development Servers

1. Open two separate terminal windows or tabs.
2. In the first terminal, navigate to the backend directory and start the Django development server:
    ```
    cd django-react-ecommerce/app/backend
    python manage.py runserver
    ```
3. In the second terminal, navigate to the frontend directory and start the React development server:
    ```
    cd django-react-ecommerce/app/frontend
    npm start
    ```

That's it! You have successfully set up and started the project. Happy coding!
