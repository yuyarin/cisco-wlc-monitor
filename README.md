# How To Use

    wlcmon <wlc_host> <snmp_community>

If you like to update periodically, for example, each 10 seconds, please use `watch` command:

    watch -n 10 wlcmon <wlc_host> <snmp_community>

# Sample Output

    [ESSID]
                SSID #Sta
         OFFICE-WLAN   45
          GUEST-WLAN   11
    [AP]                              2.4g(b/g/n)       5.0g(a/n)
    Name       Address      Status    Ch# #Sta TxPwr    Ch# #Sta TxPwr   
    ap01       10.0.5.49        Up      6    2 ||||||    48   14 ||||||| 
    ap02       10.0.5.50        Up     11    4 ||||||    36    9 ||||||| 
    ap03       10.0.5.51        Up     11    0 |||||     44   12 ||||||| 
    ap04       10.0.5.52       Down     1    2 |||||     40    8 ||||||  
    ap05       10.0.5.53     Disabled   1    0 ||||      48    5 ||||||  
    
    [Mobile Station]
    Vendor              #     %
    Apple              25  57.7
    Intel Corporate     6  11.5
    Apple, Inc          5   7.7
    Murata Manufactu    5   7.7
    HTC Corporation     3   3.8
    Slim Devices, In    3   3.8
    Buffalo Inc.        3   3.8
    Panasonic Mobile    3   3.8

# Requirement

* Ruby >= 2.0.0-p247
    * SNMP Library for Ruby >= 1.1.0
