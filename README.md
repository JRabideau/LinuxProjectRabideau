# LinuxProjectRabideau
Joshua Rabideau's Linux Server configuration project for Udacity Full Stack Web Development Nanodegree program.

Ip Address: 99.79.77.215

SSH Port 2200


Web Address:http://99.79.77.215.xip.io/

The server runs on Amazon LightSail. I installed Postgres and Apache as instructed as well as all packages necessary for previous project including:
Flask,
Oauth2Client,
SQL Alchemy,
Psycopg2-binary and
Request.
I looked up information on how to change ssh port on GoDaddy.[https://www.godaddy.com/help/changing-the-ssh-port-for-your-linux-server-7306]. My mentor also gave me good advice on how to configure my app.

I changed the SSH port to 2200 and blocked all ports except 2200, 80 and 123. I added key pairs for grader user. I configured apache to redirect to my app.

