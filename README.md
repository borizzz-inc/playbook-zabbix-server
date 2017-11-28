ansible-playbook -i inventory main.yml -D


zcat /usr/share/doc/zabbix-server-pgsql/create.sql.gz | psql -U tvil zabbix -W