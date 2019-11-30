# OpenVPN-Web-Status

A PHP based OpenVPN web status to monitor active OpenVPN connection.
<br>
<img src="https://user-images.githubusercontent.com/17911448/69898634-aab70580-1364-11ea-81f7-9bbd3dd26582.png" title="Login screen">
<br>
Appearance might be slightly different due to optimizations
<img src="https://user-images.githubusercontent.com/17911448/69904230-ce05a300-13ac-11ea-9701-05c503064e69.png" title="Status monitor view">

## Installation

Add this line on OpenVPN server configuration:
<br>
```
sudo nano /etc/openvpn/server.conf
```
add line
```
management localhost 5555
```
Then restart your OpenVPN service

You can change login password in line 53 in the php file
