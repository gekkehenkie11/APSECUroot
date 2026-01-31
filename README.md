Find out the IP of your ECU, replace my IP with yours in the following URL and open the link in your browser:
http://192.168.0.16/index.php/management/upgrade_ecu

Then upload the .bz2 file. After it executed the "update", the root password changed to 'newpassw', so telnet to your IP with root and 'newpassw' as password.

Explanation: the updater will extract the contents to the /tmp directory and the execute /tmp/update_localweb/assist, which was replaced with a script to change your root password
Of course you can replace my 'assist' script with your own if you'd want to.
