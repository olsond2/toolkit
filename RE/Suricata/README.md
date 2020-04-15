# Suricata

## Description
Suricata is an IDS similar to Snort. As packets are coming in, suricata matches rules and depending on the rules it will allow, deny, or alert on the packets. It can also do things such as download HTTP objects, etc.
<br />
<br />

## Personal Review
The way I used Suricata was very basic. It seems like Suricata would work well with a bunch of different scenarios. It was easy to set up but with complex networking it could be harder.
<br />
<br />

## Usage
1. Create a rule in a file. For example, put "alert http any any -> any any" into a file and save it as your rules file
2. Run Suricata on a pcap file

```
sudo suricata -S <rulefile> -r <file.pcap>
```
3. Check the log file in `/var/log/suricata/fast.log`
<br />
<br />

## Resources
https://github.com/OISF/suricata
