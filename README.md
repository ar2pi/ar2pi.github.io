# ar2pi.github.io##########################################################################
  IP2Location - Command Line Interface

  Website: https://www.ip2location.com
  Email:   support@ip2location.com

##########################################################################

INSTALLATION:
1. Copy ip2location.exe and IP2LOCATION-LITE-DB1.BIN to a folder


COMMAND SYNTAX:
 ip2location.exe -datafile <IP2Loation_database>
                 -inputfile <IP_list_input_file>
                 -ip <single_IP_address>
                 -outputfile <output_file_name>
                 -format <output_format>
                 -help
                 -version

   -datafile   Specify the path of IP2Location .BIN data file

   -inputfile  Specify an input file with IP address list

   -ip         Specify an IP address query (Supported IPv4 and IPv6 address)

   -outputfile Specify output file for query results

   -format     Specify output format
               Default format is comma delimited (CSV)
               Supports CSV, TAB or XML
               
   -help       Display this help file

   -version    Display the version number

   
EXAMPLES:
1) Query IP address 8.8.8.8 and show result to screen
   
   ip2location.exe -datafile IP2LOCATION-LITE-DB1.BIN -ip 8.8.8.8

2) Query all IP addresses from filename IP.LIST and show result to screen

   ip2location.exe -datafile IP2LOCATION-LITE-DB1.BIN -inputfile IP.LIST
   
3) Query all IP addresses from filename IP.LIST and show result to screen in XML format

   ip2location.exe -datafile IP2LOCATION-LITE-DB1.BIN -inputfile IP.LIST -format XML

4) Query all IP addresses from filename IP.LIST and show result in file OUTPUT.LIST in TAB format

   ip2location.exe -datafile IP2LOCATION-LITE-DB1.BIN -inputfile IP.LIST -format TAB -outputfile OUTPUT.LIST


UPGRADE:
Complete and up-to-date commercial database is available upon subscription from https://www.ip2location.com.

Free LITE database is available at https://lite.ip2location.com.

For more details, please visit:  
https://www.ip2location.com/free/applications  

Copyright (c) IP2Location.com 2001-2021. All Rights Reserved.

