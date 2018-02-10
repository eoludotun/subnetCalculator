
 PowerShell function that can convert a subnet mask from its Decimal Netmask to the CIDR “/” notation. This works for ANY Netmask length.


git clone https://github.com/eoludotun/subnetCalculator.git
  
     
         Then cd -> to the directory
         But should the name not display properly , please rename it with .ps1
         run below commands 
        

     .EXAMPLE 
          .\subnetCalculator.ps1 -IPAddress 192.168.0.1 -NetMask 255.255.255.0 
        
          
          
          
          
          Sample output =
          
          
                       
                                 Address   : 192.168.0.1
                                 Netmask   : 255.255.255.0
                                 Wildcard  : 0.0.0.255
                                 Network   : 192.168.0.0/24
                                 Broadcast : 192.168.0.255
                                 HostMin   : 192.168.0.1
                                 HostMax   : 192.168.0.254
                                 Hosts/Net : 254


