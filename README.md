# Superheroes-Codes-Challenge

# Superheroes API
The Superheroes API is a web-based application that enables you to track superheroes and their superpowers. It is built using Ruby on Rails and supports JSON responses.

# Table of Contents
Requirements Setup Models Validations Routes Getting Started Author License Requirements To use this API, you need a computer that runs on either Windows 7+, Linux, or Mac OS.

# Run on Local
To run the application on your local machine, follow these steps:

Clone the repository and open the code. Run bundle install in the terminal to install all the necessary gems specified in the Gemfile.lock file of a Ruby project. Run database migrations by running the command rails db:migrate. Seed the database by running the command rails db:seed. Start the server by running the command rails s. Open the browser and go to http://127.0.0.1:3000. Add either heroes or powers to the end of the URL to access the respective data. For example: http://127.0.0.1:3000/heroes.

# Models
The application has two models: Hero and Power. The Hero model represents the superhero, while the Power model represents the superpower.

# Validations
The application validates that the Hero has a name, a real name, and an alias. The Power model also validates that the superpower has a name and a description.

