> crontab -l

# execute every minute
*/1 * * * * /home/oracle/dba/karao/scripts/expand.sh oltp1

# execute every 2 minutes
*/2 * * * * /home/oracle/dba/karao/scripts/reduce.sh oltp1

