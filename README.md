# ENTR-451: Intro to Web Apps

- Using this repository as a template, create a web-apps repo in your GitHub account and open the project in Gitpod.
- Upon opening in Gitpod, run `rails db:setup` to setup the database, then `rails runner scripts/create_data.rb` – have a look at this script to see what data is being created when the script is executed – expected output of this script is "There are now 3 companies and 4 contacts."

- Add: resourses "tacos" in config\routes.db
- terminal: rails generate controller tacos
- Add: def index (newline) end
- Add: index.html.erb inside the views\dice
- rails server (to launch the web app)
- inside HTML: <% {ruby code that DOES NOT print to the web} %>
- inside HTML: <%= {ruby code that DOES print to the web} %>