# postgres
postgres


>> install postgresql

brew install postgresql


Start services

>> brew services start postgresql


Stop services

>> brew services stop postgresql

Create Root user

>> psql postgres


CREATE ROLE newUser WITH LOGIN PASSWORD ‘password’
ALTER ROLE newUser CREATEDB;


>> QUIT
\q 

>> login using newuser

psql postgres -U newuser

>> \du

View users and access levels
