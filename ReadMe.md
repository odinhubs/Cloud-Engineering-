### Name: Timothy Mba
### AltSchool ID: ALT/SOD/023/1126 
# Cloud Engineering Second Semester Examination Project
This document gives an overview of the cloud engineering second semester examination project process. Before I go into details, I’d give a summary of the processes involved;
1. Set up two servers; Master and slave.
2. Configure the virtual machines.
3. Create a bash-script file on the master server to automate and deploy configurations.
4. Create playbook on the master server to automate process of deploying bash-script on the slave server. 
## Details
1. Set up and configure Vagrant on master(192.168.33.10) and slave(192.168.33.20)
2. Create bash-file to automate process of deploying Laravel application
3. Install Apache, php modules and extensions, mysql server and git using ‘sudo’
4. Set up MySQL Database
5. Install composer and packages
6. Clone the Laravel application from Github
7. Install other composer dependencies into the laravel application
8. Create .env file and configure .env database
9. Set the path to .env file and alter it
10. Fetch API key value
11. Change user and file permissions 
12. configure the laravel.conf file
13. Enable laravel.conf for apache2 server and laravel application
14. Add database.sqlite file for database and changing of ownership
15. Navigate into laravel directory
16. Migrate all files and dependencies and restart apache server to get the application spinning up
17. Run command `./bashfile`
18. Set up playbook on master server to deploy laravel app into slave server
19. Run command `ansible-playbook -i hosts appbook.yml`
