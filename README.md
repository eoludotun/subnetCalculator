Steps:
  git clone https://github.com/eoludotun/subnetCalculator.git
  
       should the name not display properly , please rename it with .ps1
         run below commands 

     .EXAMPLE 
       subnetCalculator.ps1 -IPAddress 10.100.100.1 -NetMask 255.255.255.0 
       subnetCalculator.ps1 -IPAddress 10.100.100.1 -NetMask 255.255.0.0 
       subnetCalculator.ps1 -IPAddress 10.100.100.1 -NetMask 255.0.0.0
