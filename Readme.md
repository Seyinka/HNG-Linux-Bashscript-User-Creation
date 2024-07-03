Linux User Creation Bash Script

`Task : Your company has employed many new developers. As a SysOps engineer, write a bash script called create_users.sh that reads a text file containing the employee’s usernames and group names, where each line is formatted as user;groups.`

Script Requirements :

`Create a  bash script called create_users.sh`

`Create users and groups with home directories and appropriate permissions and ownership.`

`Generate random passwords for the users.`

`Log all actions to /var/log/user_management.log`

`Store passwords securely in /var/secure/user_passwords.txt`

`Handle errors, such as existing users, and log these errors.`

Explanation:

`To accomplish this, I first declared users and groups arrays to store You used the user and group arrays to store the usernames and group names read from the input file which allows to keep track of each user and their associated groups as you processed the input file, ensuring that users could be created and then added to their respective groups, including handling their password generation and logging actions accordingly. I then defined the input file, the log file, and the password file and went on to create a function to log messages to the log file and another function to generate random passwords.`

`Next, I set up the log file and password file with appropriate permissions. I added a while loop to read the input file line by line. Within this loop, the script creates users and their groups as specified.`

`The script then adds the users to their groups and generates a random password for each user. Finally, it includes error handling to log any issues encountered during user and group creation to the user_management.log file.` 

https://hng.tech/internship
 https://hng.tech/hire,



