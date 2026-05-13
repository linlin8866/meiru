bash <(curl -sL https://raw.githubusercontent.com/linlin8866/meiru/main/ip.sh)



proxies:
  - name: Mieru-TCP
    server: 你的服务器IP
    type: mieru
    port: 你的端口
    transport: tcp
    username: "你的用户名"
    password: "你的密码"
    udp: true

  - name: Mieru-UDP
    server: 你的服务器IP
    type: mieru
    port: 你的端口
    transport: udp
    username: "你的用户名"
    password: "你的密码"
    udp: true
