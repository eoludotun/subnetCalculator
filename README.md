git clone https://github.com/eoludotun/subnetCalculator.git
  
     
         Then cd -> to the directory
         But should the name not display properly , please rename it with .ps1
         run below commands 
         

     .EXAMPLE 
          .\subnetCalculator.ps1 -IPAddress 10.100.100.1 -NetMask 255.255.255.0 
          .\subnetCalculator.ps1 -IPAddress 10.100.100.1 -NetMask 255.255.0.0 
          .\subnetCalculator.ps1 -IPAddress 10.100.100.1 -NetMask 255.0.0.0
          
          
          
          
          Sample output =
          
          
                       
                          Address   : 10.100.100.1
                          Netmask   : 255.0.0.0
                          Wildcard  : 0.255.255.255
                          Network   : 10.0.0.0/8
                          Broadcast : 10.255.255.255
                          HostMin   : 10.0.0.1
                          HostMax   : 10.255.255.254
                          Hosts/Net : 16777214


