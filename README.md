Task: <br />
create a web application that has at least 5 different flaws from the OWASP top ten list as well as their fixes. <br />
I am using 2021's top ten list.

<br />
To run the application, first:

`python3 -m venv venv`<br />
`source venv/bin/activate`<br />
`pip install flask`<br />

then:

`flask init-db`

finally:

`flask run`

If there is an error, try first:

`sqlite3 database.db < schema.sql`
