# -该程序用于川崎机器人与上位机进行socket通讯，机器人作为服务器，PC段作为客户端。
通讯流程：

1.socket（）     //

2.blind（）      //

3.listen（）   TCP_LISTEN  返回值变量，端口号   

4.accept（）   TCP_ACCEPT 返回值变量，端口号，超时时间，客户端IP地址数组变量   发送/接收数据

5.recv（）     TCP_SEND 返回值变量，套接字号，接收数据的字符串变量数组，元素数，超时时间

  send（）     TCP_SEND 返回值变量，套接字号，发送数据的字符串变量数组，元素数，超时时间断开

6.sockclose（）TCP_CLOSE  返回值变量，套接字号
  
  强制关闭close（）  TCP_END_LISTEN 返回值变量，端口号
