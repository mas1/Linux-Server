# Linux-Server
  * this simple server hosts a catalogging webapp complete with oauth.
  * URL: http://ec2-34-201-9-70.compute-1.amazonaws.com/

## Grader instructions:
  * ssh to 34.201.9.70 using the username 'grader' and supplied key.
  * keyPair password: password,
  * sudo password: grader

## Configurations
  * updated all packages 
  * changed SSH port from 20 to 2200
  * configured ufw to only allows connections for ssh (2200), html (20), and ntp (123)
  * created grader user and gave them sudo permissions
  * forced grader user to use SSH key to login

## Installed software:
  * flask
  * apache
  * sqlalchemy
  * httplib2
  * google services


