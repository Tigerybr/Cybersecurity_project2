# Cybersecurity_project2
CSCI 3404 Intro to Cybersecurity

1. By typing: `ssh-keygen -t rsa` into Terminal can generate RSA keys.

2. After the execution in the Terminal, I get Keys & Keys.pub where Keys is the private key and Keys.pub holds the public key in a different format.

3. Then I used: `ssh-keygen -e -m PEM -f Keys.pub > Pubkeys.pub` to generate the public key in the same format as the Key (private key) Opening the files will make more sense than my description
