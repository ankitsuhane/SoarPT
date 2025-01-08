There are 3 jmx files
1. Client Reg: This script can perform load testing on endpoint /client_register
2. Client Login: This script can perform stress testing on /client_login
3. ClientRegLogin: This script can demonstrate user behaviour where he first register and then login. Customer registration is done with the random data.
   In order to genrate random data a script is written.
   To generate the report, please use this command in your shell script
   1. touch results.jtl
   2. jmeter -n -t clientRegLogin.jmx -l results.jtl -e -o /report_gen_path
You will get a report generated in below format
![image](https://github.com/user-attachments/assets/1e41af00-4be4-46d6-93a9-a7fbe2db63b4)
