# ArduinoWX
Arduino WX with ElasticSearch, APRS/CWOP, and other functions.  This is mostly to support sensor(s) that I'm deploying myself at either my home or other locations with IP connectivity.

Expectations for each:

ElasticSearch: public all metrics on a set interval to a ES endpoint
APRS: APRS-IS posting
CWOP: post to CWOP for non-amateur radio ops

Planned function support:
v.01 - Temp/Baro/Humidity, NTP source, ES and APRS
v.02 - GPS for time and location, CWOP
v.03 - Battery health monitoring/Solar power support
v.04 - Wind & Rain sensors
