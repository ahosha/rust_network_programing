to run tcp server :  from src directory , run ``` rustc tcp_echo_server.rs && ./tcp_echo_server  ```
ro run tcp client :  from src directory , run  ``` rustc tcp_client.rs && ./tcp_client ```


to run udp server :  from src directory , run ``` rustc udp_echo_server.rs && ./udp_echo_server  ```
ro run udp client :  from src directory , run  ```rustc udp_client.rs && ./udp_client  ```

you can use nc to interact with tcp or udp server
tcp: ``` nc 127.0.0.1 888  ```
udp: ```   nc -u 1247.0.0.1 8888   ```

