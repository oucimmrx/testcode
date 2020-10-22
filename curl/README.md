# curl
https://curl.haxx.se/  
This is more of a tool than a language but I wanted to include an example to get request statitics using this tool.

# To run the example
open the terminal and execute the following commands
> curl -w "@curl-format.txt" -o /dev/null -s www.google.com  

sample output
> time_namelookup:  0.004109s  
time_connect:  0.007004s  
time_appconnect:  0.000000s  
time_pretransfer:  0.007039s  
time_redirect:  0.000000s  
time_starttransfer:  0.050867s  
\----------  
time_total:  0.053241s

