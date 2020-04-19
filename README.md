# install-postgresql

<b> 
  Note:
  </b>

<p>
This script installs the PostgreSQL on CentOS 7, 8 and Ubuntu 18.04 <br />
Blog Site: https://smarttechfunda.com/how-to-install-postgresql-on-centos-and-ubuntu/ <br />
The install-postgresql script takes the following input from the user and perform operations. <br /> 
1. Database user name <br />
2. Database name <br />
3. Assign the entered user as database owner (y/N) <br /> 
4. Assign the CREATEROLE, CREATEDB and SUPEUSER privilges (y/N)<br /> 
5. Allow remote access to the database (y/N)<br /> 

Also, the blog site has all above commands with examples.
<p/>

<b> How to run the script? </b>
<p>
git clone https://github.com/smarttechfunda/install-postgresql.git
<p/>
<p>
Login as a non-root user, and the user should have sudo permission.<br />
OR <br /> Use sudo su command to login as root user. <br />
Run the following command. (If you are login as root user then no need to use sudo command.)<br />
$ cd install-postgresql <br />
$ chmod +x install-postgresql <br />
$ sudo ./install-postgresql <br /> 
<p/>
