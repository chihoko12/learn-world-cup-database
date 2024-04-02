pg_dump -cC --inserts -U freecodecamp worldcup > worldcup.sql 
psql -U postgres < worldcup.sql
