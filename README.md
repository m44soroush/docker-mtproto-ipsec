# docker-mtproto-ipsec


You can use this docker-compose to have l2tp/ipsec VPN and Mtproto proxy for telegram.

## How to use this docker compose file?
1. Install docker and docker-compose.

2. Clone this repo


3. Enter your desired usernames and passwords in `vpn.env` file


4. Run docker compose file:
  ``` 
  $ docker-compose up -d
  ```
  
5. Check logs to  get IKEv2 connection information and Mtproto secret:
  ```
  $ docker-compose logs
  ```  
    
**Note:** For more information please visit these links:
- https://github.com/hwdsl2/docker-ipsec-vpn-server
- https://github.com/TelegramMessenger/MTProxy
