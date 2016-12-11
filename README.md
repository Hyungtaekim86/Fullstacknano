# Fullstacknano

Instruction to successfully run the Tournament Application

1. Make sure to install Vagrant and Virtual Box
2. Clone the fullstack nanodegree repository here: http://github.com/udacity/fullstack-nanodegree-vm
3. Launch Terminal and go to the fullstack/vagrant/tournament directory (the forked directory)
4. Load Vagrant with "Vagrant Up" command
5. Log on to Vagrant with Vagrant ssh
6. Type "psql" on the command line to access postgreSQL
7. on the PSQL commandline, type \i tournament.sql; 
8. This should import the database in tournament.sql file to postgreSQL.
9. Quit PSQL commandline by \q
10. Now, load the test file by "python tournament_test.py" command
11. the END
