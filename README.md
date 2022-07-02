1 - download openvpn-install.sh on your server

2 - give run permmition to openvpn-install.sh

```
chmod +x openvpn-install.sh
```

3 - to run use following command

```
sudo ./openvpn-install.sh
```

4 - follow installation  wizard

5 - run again openvpn-install.sh to add or remove user 

6 - to enable openvpn service use following command

```
systemctl enable openvpn@server.service
```

7 - to check openvpn service status use following command

```
systemctl status openvpn@server.service
```

8 - to restart openvpn service use following command

```
systemctl restart openvpn@server.service
```

9 - to stop openvpn service use following command

```
systemctl stop openvpn@server.service
```

