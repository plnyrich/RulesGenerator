# Rules Generator
Simple Python script, which takes mining pool lists as input, and verifies if the IP and port truly belong to the mining pool server. Verification is done via active probing - Stratum request and the reply is checked. The script can be periodically run via CRON. Verified pairs are written to the output file and can be used for traffic capture or filtering.

## Acknowledgements
This research was funded by the Ministry of Interior of the Czech Republic, grant No. VJ02010024: Flow-Based Encrypted Traffic Analysis and also by the Grant Agency of the CTU in Prague, grant No. SGS20/210/OHK3/3T/18 funded by the MEYS of the Czech Republic.