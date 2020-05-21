# esp32_tcp_test

## 测试中的一些故障排除
- 连接wifi故障，可能原因：
    - wifi中文名称
    - 需要将某些路由器掉电重启才能连上
- `E (5588) example: Socket unable to connect: errno 104`故障，可能原因：
    - 服务器端`nc -l 192.168.1.107 3333`命令需要重启
