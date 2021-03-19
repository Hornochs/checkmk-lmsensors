# checkmk_lmsensors

Local Check for CheckMK, to get all values from lmsensors. 

Needed: https://github.com/bastienleonard/pysensors

Working Python3

installed lmsensors

It's recommended to write a config file for lmsensors (/etc/sensor3.conf unter debian) to create matching labels! Makes the output quite readable :) 

This local check needs to be placed on the check_mk_Agent/local folder. For Debian it's: /usr/lib/check_mk_agent/local