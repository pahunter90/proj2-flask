# proj2-flask

Takes a syllabus (schedule) and uploads it to a tabled format
  with the current week highlighted in purple. 
  The schedule should be located in syllabus/data and should be formatted as follows:
  week: #(integer)
  topic: topic for that week (can be blank)
  project: project for that week (can be blank)
  Extra lines are okay, as are lines that start with # (hash)

Author: Pierce Hunter
Contact: phunter@uoregon.edu
Code Skeleton (most of the code): Michael Young

To run the program (as a server):
  Clone the git
  change credentals-skel.ini to your own credentials.ini and place in syllabus/
    -fill out appropriate locations
  make install
  make start
To shut down the server
  make stop

Designed for use on Raspberry Pi 2 or 3 with python3 installed
Uses flask and arrow

To run the program (virtual environment)
  Clone git
  credentials.ini (see above)
  make install
  source env/bin/activate
  pip install -r requirements.txt
  make start
To shut down server and end virtual environment
  make stop
  deactivate
