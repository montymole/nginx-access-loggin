#nginx access_log examples

Simple ways how to use access_log and log_format directives to create csv log file. 

# prerequisites

nginx installed

## tracker example

run

cfg=$(pwd)/tracker.conf;sudo nginx -s stop;sudo nginx -c $cfg

## save data example
run

cfg=$(pwd)/savedata.conf;sudo nginx -s stop;sudo nginx -c $cfg;tail -f /tmp/dat.csv




