# redis-lab
#GUI tools like DBeaver can be used to navigate within redis-server

#But for remote connection, redis-server should be run with disabling protected mode 
to do so, use redis-cli
inside redis-cli> CONFIG SET protected-mode no

#to start redis-server run script located inside 
 /usr/local/bin/redis-server /etc/redis/6379.conf
#to stop redis-server run script as
 /usr/local/bin/redis-cli shutdown
 
 to run in backgroud 
redis-server --daemonize yes
