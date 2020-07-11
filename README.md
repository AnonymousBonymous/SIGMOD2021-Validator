# SIGMOD2021-Validator
Validator for SIGMOD2021 log files
As program arguments accepts:
- required: path to log file 
- optional: path to spark config file
- optional: flag "-p" to only output precision

Outputs result file as: inputLogFile+".res"

example:
All commands (sbt run ../SIGMOD2021/yelp.log spark.conf -p)
Normal log output (sbt run ../SIGMOD2021/yelp.log) outputs to ../SIGMOD2021/yelp.log.res
