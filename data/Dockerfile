FROM st2
LABEL com.stackstorm.service.provides="data"

ADD ./st2.conf /etc/st2/st2.conf
ADD ./htpasswd /etc/st2/htpasswd

CMD st2-register-content --config-file /etc/st2/st2.conf --register-all
