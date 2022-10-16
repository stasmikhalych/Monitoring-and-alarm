              #     Monitoring and troubleshouting node system

1.	Server hardware monitoring.
I’m using 3-d party commercial system to monitor server:
In most cases this is more convenient then own developed. Due to the following reason:
-	No need to install additional web server for remote access. Installing web-services to monitor server exactly on server – huge whole in security system. It’s necessary to install web-server, databases, any monitoring agent which sometimes working not as expected.
-	Notification system will not work in case of server shut down, so anyway need to have remote notification server
-	If any troubles – much easy and convenient way to ask support team!
Some other reasons, mostly because I’m not software developer, easy and finally  more cheaper to use commercial solutions.

To not provide advertising to solution I’m using – just share some screenshots with monitoring information.
Pic. 1 General server information. This information exactly from HAQQ testedge validator server ( you can see in right side server information including ip ) 
![Alt text](/img/monitor1.png?raw=true "General server information")

Pic 2.  Process monitoring.
![Alt text](/img/monitor2.png?raw=true "Process monitoring")

Pic.3 CPU loading monitoring. 
![Alt text](/img/monitor3.png?raw=true "CPU load monitoring")

Pic 4 Network Utilization
![Alt text](/img/monitor4.png?raw=true "Network utilization")

As of notification, sms, email and even call ( I’m not on this option )

Pic 5. Email notification system in action
![Alt text](/img/email_notif.png?raw=true "Email notification")

2.	Validator troubles notification.
  The main trouble we need to monitor in realtime, 24/7  – missed blocks. 
Thanks to guys for telegram-bots.

False alarm screenshot, I stopped  haqqd service for a couple of sec.

Pic.6 False alarm screenshot
![Alt text](/img/falsh_alarm.png?raw=true "False alarm")

