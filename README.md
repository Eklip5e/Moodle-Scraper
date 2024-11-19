# Moodle-Scraper
A small project, made in Python to download all your courses locally, in a snap

# Why you made this?
It's just a plain explaination on how moodle servers can be sort of exploited to do what you need without a GUI, simply put in the ```.env``` file your login informations (aka, **Username** and **Password**) and open the python script.

# How does it work?
Once you load the python script, it logs in your Uni website with the previously set credentials, it automatically checks every course you're enrolled, prints and saves locally a file with all the courses link.
Since everything has a url, it just opens all the course one by one and scrapes everything it finds, again, this time the script tells every file and text message inside the course, and it saves it locally.
But it's not clean, the script saves the course file inside a folder called as the course name, and it contains characters and the year of the course

### Ex. : Sistemi Operativi - [2024/2025] - Resto 1

Once the process is done, the script creates a config file, where you can fix this problem manually, you summarize the name from a long string to just the course name.

The script will close and if you need to apply this fix, simply open it again, it won't make any duplicates, it will only check if everything is downloaded, then it moves everything inside the folders you set manually before.

# Do I really need this?
tl;dr: if you're lazy and you need something that downloads everything inside of the course, without opening file after file, downloaing them, save and move them manually, this does it all automatically
