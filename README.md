# VPN-setup-for-Windows-10

## Instructions
Setup VPN

In VPN settings select “add VPN Connection”.

- https://documentation.meraki.com/MX/Client_VPN/Client_VPN_OS_Configuration


  1. Fill in the required fields reflecting the VPN server settings.

  2. In Elevated Command Prompt run the follow command replacing {} with the value.

netsh interface ipv4 add route {IP} {VPN Name}

netsh interface ipv4 add route 192.168.0.0/24 "QUADNET VPN"

### Remember to elevate command prompt by running it as admin.

# Related articles
- Page: 
  
[Enroll Windows 10/11 devices in Intune](https://learn.microsoft.com/en-us/intune/intune-service/user-help/enroll-windows-10-device)
- Page:
  
[Trend Micro Email Security - Block Sender](https://docs.trendmicro.com/en-us/documentation/article/trend-micro-email-security-online-help-configuring-approved)
- Page:
  
[Site-to-Site VPN (Meraki to Azure)](https://documentation.meraki.com/MX/Site-to-site_VPN/Site-to-Site_VPN_Settings)
- Page:
  
[Windows Network - Unauthenticated](https://learn.microsoft.com/en-us/answers/questions/1348111/windows-10-unidentified-and-unauthenticated-networ)
- Page:
  
[SMTP Relay](https://sendgrid.com/en-us/blog/smtp-relay-service-basics)
