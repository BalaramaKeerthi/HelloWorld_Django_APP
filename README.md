# Django Hello World App

This is a simple Django web application that returns a JSON object with a "Hello World!" message.

## How to Run/Start the Web App

1. **Clone the Repository:**
```sh
git clone <repository_url>
```
Replace `<repository_url>` with the URL of the GitHub repository.

2. **Navigate to the Project Directory:**

```sh
cd helloworld_project
```

4. **Run Database Migrations:** 
```sh
python manage.py migrate
```

6. **Start the Development Server:**
```sh
python manage.py runserver
```
8. **Accessing the Hello World JSON Response:**
- Once the development server is running, open a web browser.
- Navigate to http://127.0.0.1:8000/ to see the Hello World JSON response.
