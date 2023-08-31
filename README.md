# LeetCode-FlashCards
A Django web app for keeping track of solved questions for easy review.

# How it works
You only need to provide the problem link, a topic to group problems by, 
and your solutions to the problem. The app will automatically generate a 
page for each problems by making GraphQL queries to leetcode/graphql server.

# Installation Guide

## Prerequisites

- Python (3.6 or higher)
- pip (Python package manager)
- virtualenv
- Git

## Installation Steps

1. **Clone the Repository**

   ```
   git clone https://github.com/enansaif/flashcards.git
   ```

2. **Create a Virtual Environment**

   ```
   python -m venv .venv
   ```

3. **Activate the Virtual Environment**

   Activate the virtual environment based on your operating system:

   - **On Windows:**

     ```
     .venv\scripts\activate
     ```

   - **On macOS and Linux:**

     ```
     source .venv/bin/activate
     ```

4. **Install Dependencies**

   Install the required Python packages using pip. Make sure
   you're in your project directory and that your virtual
   environment is activated:

   ```
   pip install -r requirements.txt
   ```
5. **Create a Superuser/Admin (Optional)**

   To create a superuser account for the Django admin panel, use the following command and follow the prompts:

   ```
   python manage.py createsuperuser
   ```

6. **Run the Development Server**

   Start the Django development server with the following command:

   ```
   python manage.py runserver
   ```

   Your app should now be running locally. You can access it by opening a web browser and navigating to `http://localhost:8000/`.

7. **Access the Admin Panel(Optional)**

   You can access the Django admin panel by visiting `http://localhost:8000/admin/` and logging in with the superuser credentials you created earlier.

## License

This Django app is provided under the [MIT License](LICENSE). You are free to use, modify, and distribute it as per the terms of the license.

## Support and Feedback

If you encounter any issues or have questions, please feel free to [open an issue](https://github.com/your-username/your-django-app/issues) on the GitHub repository.

Happy coding! 🚀