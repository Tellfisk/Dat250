
## Software Development Environment
I had to install *JDK*, *Git* and *Maven*, as I didn't have those  from before (new computer). Maven went smooth, but I had some trouble setting the *JAVA_HOME* path. After some googling and command prompting it was all set, and "mvn --version" finally gave me no errors. That's how I verified everything had installed successfully.

## Heroku
Registration and installation was easy enough. Very clean UI on the webpage.
"heroku pg:psql" didn't work at first so I had to install *PostgreSQL*, which took some time, and somespace on my computer. PostgreSql proved to be a bit unintuitive (atleast to me) when it comes to installing the right packages, the right version and so on. I finished by visiting the */db* branch of our sinmple app, and then checking the database by running command "SELECT * FROM tick;" in the database, and verifying that it worked. 
