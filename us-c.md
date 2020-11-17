git clone repo_name --config core.sshCommand="ssh -i /root/cb_rsa"

create database ви_тфь;
CREATE USER ви_тфь WITH ENCRYPTED PASSWORD 'ви_тфь';
GRANT ALL PRIVILEGES ON DATABASE exp_dictionary TO ви_тфь;
ALTER USER ви_тфь WITH SUPERUSER;

SHELL=/bin/sh
PATH=/usr/local/sbin:/usr/local/bin:/sbin:/bin:/usr/sbin:/usr/bin
* * * * * root /usr/bin/flock -E 0 -w 30 /tmp/.stuffapp.lck bash /usr/share/engine/bin/stuffapp.sh >> /var/tmp/stuffapp.err 2>&1

