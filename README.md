# Assessment01 

Overview


traveler.  A WAN based road warrior user running Windows 10. (this replaces the linux rw01)

edge01.  A vyOS Firewall with three interfaces (WAN, DMZ, LAN).  You will need to add an interface using vCenter. (this replaces fw01)

nginx01.  A DMZ based nginx web server running Ubuntu (this replaces web01 and apache)

dhcp01.  A LAN based dhcp server running Ubuntu



# Phase 1: Connections

# Phase 2: Services

ngix install

```
sudo apt update
sudo apt install nginx
```

```
sudo ufw app list
```

```
sudo ufw allow 'Nginx HTTP'
```

Web page asccessible at http://`serverIP`
