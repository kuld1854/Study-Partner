# Study-Partner

Study-Partner is a project inspired by a tutorial series by Traversy Media on YouTube. It aims to replicate the basic functionality of Discord, providing features like user registration and login, channel creation and management, as well as sending and receiving messages.

## Getting Started

Follow these steps to clone and set up the project on your local machine:

1. Clone the repository using the following command:

   ```bash
   git clone https://github.com/kuld1854/Study-Partner
   ```

2. Move into the directory where the project files are located:

   ```bash
   cd Study-Partner
   ```

3. Create a virtual environment to isolate project dependencies:

   ```bash
   # Install virtualenv (if not already installed)
   pip install virtualenv

   # Create a virtual environment (replace "envname" with your preferred name)
   virtualenv envname
   ```

4. Activate the virtual environment:

   - On Windows:

     ```bash
     envname\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source envname/bin/activate
     ```

5. Install the project's requirements:

   ```bash
   pip install -r requirements.txt
   ```

## Running the App

To run the Study-Partner app, use the following command:

```bash
python manage.py runserver
```

This will start the development server, and you can access the app at [http://127.0.0.1:8000/](http://127.0.0.1:8000/).

⚠ Please note that this is a simplified clone project for educational purposes and may not have all the features and security measures of the real Discord application. Use it responsibly and ensure proper security practices when deploying similar applications.
