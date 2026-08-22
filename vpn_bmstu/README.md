vpn for intertnal bmstu network

### setup on ubuntu:

to connect:
```bash
$ openvpn3 session-start --config bmstu.ovpn
```

to disconnect:
```bash
$ openvpn3 session-manage --disconnect --config bmstu.ovpn
```
