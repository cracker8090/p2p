# p2p
Complete udp to pass NAT by golang



# example

```go
  Server S
                    47.116.8.77:9981
                           |
                           |
    +----------------------|----------------------+
    |                                             |
  NAT A                                         NAT B
14.30.48.77:57449                            27.38.252.190:26932
    |                                             |
    |                                             |
 Client A                                      Client B
 172.20.10.3:9982                                 192.168.100.103:9982
```

# UDP pcap



![](https://raw.githubusercontent.com/cracker8090/imgbed/master/blogImg/20200831170342.png)



![](https://raw.githubusercontent.com/cracker8090/imgbed/master/blogImg/20200831170453.png)      

 