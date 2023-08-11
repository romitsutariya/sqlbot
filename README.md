# SQL Bot: Simplifying SQL Query Creation with Natural Language using Python and ChainLit
## Text to SQL

SQL Bot is a user-friendly Python application that utilizes ChainLit, a powerful natural language processing library, to make creating SQL queries a breeze. Say farewell to the intricacies of SQL syntax – SQL Bot understands your intent and generates accurate SQL queries effortlessly.

## Features

- ***ChainLit Integration***: Leveraging the capabilities of ChainLit, SQL Bot translates your natural language input into precise SQL code, creating a seamless interaction between you and your database.
- ***Intuitive Interface***: The user interface is designed to provide a straightforward experience. Just input your query in plain English, and let SQL Bot handle the rest.
- ***Real-time Suggestions***: SQL Bot offers intelligent query suggestions as you type, aiding you in refining your query and boosting your productivity.
-  ***Multi-database Support***: SQL Bot supports various databases including MySQL, PostgreSQL, SQL Server, and more, ensuring compatibility with your preferred database system.
- ***Query Management***: Save frequently used queries, share them with your team, and organize your queries efficiently.

## Getting Started
***Installation***: Clone the repository and install the required dependencies by executing the following commands:
Sql Bot requires [Python](https://www.python.org/) 3.11+ to run.
  ```sh
    git clone https://github.com/romitsutariya/sqlbot.com
  ```
## PIPENV
OK, installing pipenv is pretty easy too: reference [pipenv](https://pipenv.pypa.io)
```sh
   pip install --user pipenv
```  
## Importing from requirements.txt
For projects utilizing a requirements.txt pipenv can import the contents of this file and create a Pipfile and Pipfile.lock for you:
```sh
pipenv install -r path/to/requirements.txt
```  
## That's it!! Run applilcation
```sh
chainlit run main.py
```  
Your chatbot UI should now be accessible at http://localhost:8000.
## License

MIT
**Free Software, Hell Yeah!**