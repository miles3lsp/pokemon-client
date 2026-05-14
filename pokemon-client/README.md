Pokemon Client App
This is just a small console app I made to practice OOP in Python. The goal was to figure out how to get data from an API and use it inside classes.

I used the requests library to grab data from PokeAPI. There's one class that handles the API connection, and another one that creates the actual Pokemon object to print its name.

I'm using uv to manage the project. It's super convenient because it runs the code fast and you don't have to mess with virtual environments manually.

How to install
Make sure you have uv installed. You can easily get it via pip:

pip install uv

How to run
Open your terminal in the project folder and run the command below. It will install everything automatically and start the app:

uv run main.py