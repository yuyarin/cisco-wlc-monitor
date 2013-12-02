# How To Use

    wlcmon <wlc_host> <snmp_community>

If you like to update periodically, for example, each 10 seconds, please use `watch` command:

    watch -n 10 wlcmon <wlc_host> <snmp_community>

# Sample Output

                SSID #Sta
         OFFICE-WLAN   45
          GUEST-WLAN   11
                                     2.4g(b/g/n)        5.0g(a/n)
    Name       Address      Status Ch#  #Sta TxPwr    Ch#  #Sta TxPwr   
        ap01    10.0.5.49     up      6    2 ||||||     48   14 ||||||| 
        ap02    10.0.5.50     up     11    4 ||||||     36    9 ||||||| 
        ap03    10.0.5.51     up     11    0 |||||      44   12 ||||||| 
        ap04    10.0.5.52     up      1    2 |||||      40    8 ||||||  
        ap05    10.0.5.53     up      1    0 ||||       48    5 ||||||  

# Requirement

* Ruby >= 2.0.0-p247
    ** SNMP Library for Ruby >= 1.1.0
