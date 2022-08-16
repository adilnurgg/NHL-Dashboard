# NHL_Dashboard

**Running Program**:
1) Download or clone repository
2) Navagate to "test" folder in the command line
3) Create the sqlite databash and dash UI by entering "python index.py"
4) A bunch of text will output, look for a website link starting with http, copy and search it in the browser. The dashboard should now be live in your browser!
5) To view the sqlite database, open the .db file in the test folder with a sqlite database viewer application

The whole system is written in **Python**. 

The **frontend** was implemented with Dash and Plotly framework. 

On the **backend** side, it firstly creates a SQLite database management system (DBMS) server and offers a library of API functions to send queries to the SQLite server.
When the user gives a command through an interface (e.g., a button) on the browser, the corresponding callback functions call the query function in the backend side.
Then, the query function sends queries to the DBMS, retrieves required data, and returns the data back to the callback functions in the frontend side. Afterwards, the
callback function uses data visualization functions to visualize the returned data and finally sends back the rendered illustrations to the interface.

**References**:

Dash Plotly. [Online]. Available: https://plotly.com/dash/.

M. Parra, “Devparra/baseball-hist-dash: MLB data explorer,” baseball-hist-dash. [Online]. Available: https://github.com/devparra/baseball-hist-dash.

M. Parra, MLB Historical Data Visualization. [Online]. Available: https://dash.gallery/dash-baseball-statistics.

P. Tanner, Money Puck. [Online]. Available: https://moneypuck.com/.

SQLite [Online]. Available: https://www.sqlite.org/index.html.

**Our team**:

Adilnur Istekov(Me) - Backend Developer

Luke Neuendorf - Backend Developer

Bo-Hsun Chen - Frontend Developer
