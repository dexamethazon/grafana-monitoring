## Configure SNMPD Service on Server

Install SNMPD

```
sudo apt install snmpd
```

Copy example config
```
sudo mv /etc/snmp/snmpd.conf /etc/snmp/snmpd.conf.dist
sudo cp snmpd.conf.example /etc/snmp/snmpd.conf
sudo cp distro /usr/bin/distro
sudo chmod +x /usr/bin/distro
```
