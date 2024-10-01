## installing package got stucked on ubuntu

1. check vpn connection
2. make sure the vpn isn't connected
3. if issue still occured then try to open Docker Desktop
4. change dns to google -> 8.8.8.8

```bash
sudo warp-cli disconnect
sudo resolvectl dns wlo1 8.8.8.8
```
