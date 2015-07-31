
# 带压缩的压测
1. 压测 100字节 网络:13MB/s cpu:366% 内存:6.7  /cpu:379% 内存:12
procs -----------memory---------- ---swap-- -----io---- --system-- -----cpu-----
 r  b   swpd   free   buff  cache   si   so    bi    bo   in   cs us sy id wa st
 2  0   7240 7219948  77480  63752    1    2     2     3    2    1  1  0 98  0  0
 1  0   7240 7219816  77488  63764    0    0     0    16 46709 72955 31 10 60  0  0
 2  0   7240 7219692  77488  63772    0    0     0     0 43606 68840 29  9 62  0  0
 4  0   7240 7219444  77488  63772    0    0     0     0 46688 73499 29 10 62  0  0
 1  0   7240 7219568  77488  63772    0    0     0     0 46978 72835 31 10 59  0  0
 4  0   7240 7219816  77488  63772    0    0     0     0 46007 72200 30  9 61  0  0


 2015-07-24 07:24:13 ready to start client benchmark,server is ,concurrents is: 100,clientNums is: 1,requestSize is:100 bytes,the benchmark will end at:2015-07-24 07:27:13
----------Benchmark Statistics--------------
 Concurrents: 100
 ClientNums: 1
 RequestSize: 100 bytes
 Runtime: 180 seconds
 Benchmark Time: 130
 Requests: 10945235 Success: 100% (10945235) Error: 0% (0)
 Avg TPS: 84194 Max TPS: 87455 Min TPS: 72139
 Avg RT: 1ms
 RT <= 0: 2% 309246/10945235
 RT (0,1]: 83% 9164539/10945235
 RT (1,5]: 12% 1419222/10945235
 RT (5,10]: 0% 642/10945235
 RT (10,50]: 0% 51586/10945235
 RT (50,100]: 0% 0/10945235
 RT (100,500]: 0% 0/10945235
 RT (500,1000]: 0% 0/10945235
 RT > 1000: 0% 0/10945235

 2. 压测 200字节 网络:14.5MB/s cpu:343% 内存:6.7  /cpu:350% 内存:12
 2015-07-24 07:48:35 ready to start client benchmark,server is ,concurrents is: 100,clientNums is: 1,requestSize is:200 bytes,the benchmark will end at:2015-07-24 07:51:35
----------Benchmark Statistics--------------
 Concurrents: 100
 ClientNums: 1
 RequestSize: 200 bytes
 Runtime: 180 seconds
 Benchmark Time: 141
 Requests: 10794786 Success: 100% (10794786) Error: 0% (0)
 Avg TPS: 74533 Max TPS: 78934 Min TPS: 67166
 Avg RT: 1ms
 RT <= 0: 0% 65218/10794786
 RT (0,1]: 72% 7872742/10794786
 RT (1,5]: 25% 2799828/10794786
 RT (5,10]: 0% 985/10794786
 RT (10,50]: 0% 56013/10794786
 RT (50,100]: 0% 0/10794786
 RT (100,500]: 0% 0/10794786
 RT (500,1000]: 0% 0/10794786
 RT > 1000: 0% 0/10794786

 3. 压测 300字节 网络:13MB/s cpu:301% 内存:6.7  /cpu:315% 内存:12
 2015-07-24 07:55:43 ready to start client benchmark,server is ,concurrents is: 100,clientNums is: 1,requestSize is:300 bytes,the benchmark will end at:2015-07-24 07:58:43
 ----------Benchmark Statistics--------------
  Concurrents: 100
  ClientNums: 1
  RequestSize: 300 bytes
  Runtime: 180 seconds
  Benchmark Time: 141
  Requests: 9605473 Success: 100% (9605473) Error: 0% (0)
  Avg TPS: 65142 Max TPS: 70502 Min TPS: 58439
  Avg RT: 1ms
  RT <= 0: 0% 8215/9605473
  RT (0,1]: 54% 5275691/9605473
  RT (1,5]: 44% 4263896/9605473
  RT (5,10]: 0% 1187/9605473
  RT (10,50]: 0% 56484/9605473
  RT (50,100]: 0% 0/9605473
  RT (100,500]: 0% 0/9605473
  RT (500,1000]: 0% 0/9605473
  RT > 1000: 0% 0/9605473

  4. 压测 500字节 网络:12MB/s cpu:272% 内存:6.7  /cpu:282% 内存:12
  2015-07-24 07:59:46 ready to start client benchmark,server is ,concurrents is: 100,clientNums is: 1,requestSize is:500 bytes,the benchmark will end at:2015-07-24 08:02:46
  ----------Benchmark Statistics--------------
   Concurrents: 100
   ClientNums: 1
   RequestSize: 500 bytes
   Runtime: 180 seconds
   Benchmark Time: 141
   Requests: 8315428 Success: 100% (8315428) Error: 0% (0)
   Avg TPS: 58224 Max TPS: 61618 Min TPS: 52076
   Avg RT: 1ms
   RT <= 0: 0% 816/8315428
   RT (0,1]: 37% 3121991/8315428
   RT (1,5]: 61% 5139300/8315428
   RT (5,10]: 0% 2341/8315428
   RT (10,50]: 0% 50980/8315428
   RT (50,100]: 0% 0/8315428
   RT (100,500]: 0% 0/8315428
   RT (500,1000]: 0% 0/8315428
   RT > 1000: 0% 0/8315428

5. 压测 1024字节 网络:9MB/s cpu:224% 内存:6.7  /cpu:222% 内存:12
  2015-07-24 08:04:09 ready to start client benchmark,server is ,concurrents is: 100,clientNums is: 1,requestSize is:1024 bytes,the benchmark will end at:2015-07-24 08:07:09
----------Benchmark Statistics--------------
 Concurrents: 100
 ClientNums: 1
 RequestSize: 1024 bytes
 Runtime: 180 seconds
 Benchmark Time: 136
 Requests: 5633545 Success: 100% (5633545) Error: 0% (0)
 Avg TPS: 41423 Max TPS: 43135 Min TPS: 24403
 Avg RT: 2ms
 RT <= 0: 0% 0/5633545
 RT (0,1]: 0% 18051/5633545
 RT (1,5]: 98% 5567728/5633545
 RT (5,10]: 0% 24639/5633545
 RT (10,50]: 0% 23127/5633545
 RT (50,100]: 0% 0/5633545
 RT (100,500]: 0% 0/5633545
 RT (500,1000]: 0% 0/5633545
 RT > 1000: 0% 0/5633545

6. 压测 2048字节 网络:5.8MB/s cpu:168% 内存:6.7  /cpu:186% 内存:12
2015-07-24 08:47:10 ready to start client benchmark,server is ,concurrents is: 100,clientNums is: 1,requestSize is:2048 bytes,the benchmark will end at:2015-07-24 08:50:10
----------Benchmark Statistics--------------
 Concurrents: 100
 ClientNums: 1
 RequestSize: 2048 bytes
 Runtime: 180 seconds
 Benchmark Time: 141
 Requests: 3898274 Success: 100% (3898274) Error: 0% (0)
 Avg TPS: 26699 Max TPS: 27933 Min TPS: 25410
 Avg RT: 3ms
 RT <= 0: 0% 0/3898274
 RT (0,1]: 0% 466/3898274
 RT (1,5]: 98% 3844469/3898274
 RT (5,10]: 0% 34456/3898274
 RT (10,50]: 0% 18883/3898274
 RT (50,100]: 0% 0/3898274
 RT (100,500]: 0% 0/3898274
 RT (500,1000]: 0% 0/3898274
 RT > 1000: 0% 0/3898274

启动两个客户端 压测 2048字节 网络:9.66MB/s cpu:308% 内存:6.8  /cpu:186% 内存:12
客户端一:2015-07-24 08:50:54 ready to start client benchmark,server is ,concurrents is: 100,clientNums is: 1,requestSize is:2048 bytes,the benchmark will end at:2015-07-24 08:53:54
----------Benchmark Statistics--------------
 Concurrents: 100
 ClientNums: 1
 RequestSize: 2048 bytes
 Runtime: 180 seconds
 Benchmark Time: 141
 Requests: 3175540 Success: 100% (3175540) Error: 0% (0)
 Avg TPS: 21839 Max TPS: 23023 Min TPS: 18773
 Avg RT: 4ms
 RT <= 0: 0% 0/3175540
 RT (0,1]: 0% 92/3175540
 RT (1,5]: 92% 2953006/3175540
 RT (5,10]: 6% 193871/3175540
 RT (10,50]: 0% 28571/3175540
 RT (50,100]: 0% 0/3175540
 RT (100,500]: 0% 0/3175540
 RT (500,1000]: 0% 0/3175540
 RT > 1000: 0% 0/3175540

客户端二:2015-07-24 08:50:52 ready to start client benchmark,server is ,concurrents is: 100,clientNums is: 1,requestSize is:2048 bytes,the benchmark will end at:2015-07-24 08:53:52
----------Benchmark Statistics--------------
 Concurrents: 100
 ClientNums: 1
 RequestSize: 2048 bytes
 Runtime: 180 seconds
 Benchmark Time: 141
 Requests: 3277127 Success: 100% (3277127) Error: 0% (0)
 Avg TPS: 22154 Max TPS: 23272 Min TPS: 20314
 Avg RT: 4ms
 RT <= 0: 0% 0/3277127
 RT (0,1]: 0% 117/3277127
 RT (1,5]: 93% 3059856/3277127
 RT (5,10]: 5% 188079/3277127
 RT (10,50]: 0% 29075/3277127
 RT (50,100]: 0% 0/3277127
 RT (100,500]: 0% 0/3277127
 RT (500,1000]: 0% 0/3277127
 RT > 1000: 0% 0/3277127

 7. 压测 5020字节 网络:2.77MB/s cpu:150% 内存:6.6  /cpu:163% 内存:12

 2015-07-24 08:56:24 ready to start client benchmark,server is ,concurrents is: 100,clientNums is: 1,requestSize is:5120 bytes,the benchmark will end at:2015-07-24 08:59:24
----------Benchmark Statistics--------------
 Concurrents: 100
 ClientNums: 1
 RequestSize: 5120 bytes
 Runtime: 180 seconds
 Benchmark Time: 141
 Requests: 1810957 Success: 100% (1810957) Error: 0% (0)
 Avg TPS: 12320 Max TPS: 12673 Min TPS: 11745
 Avg RT: 8ms
 RT <= 0: 0% 0/1810957
 RT (0,1]: 0% 6/1810957
 RT (1,5]: 1% 20450/1810957
 RT (5,10]: 95% 1737165/1810957
 RT (10,50]: 2% 53336/1810957
 RT (50,100]: 0% 0/1810957
 RT (100,500]: 0% 0/1810957
 RT (500,1000]: 0% 0/1810957
 RT > 1000: 0% 0/1810957

 3客户端  压测 5020字节 网络:6.0MB/s cpu:444% 内存:6.6  /cpu:163% 内存:12

 2015-07-24 09:00:10 ready to start client benchmark,server is ,concurrents is: 100,clientNums is: 1,requestSize is:5120 bytes,the benchmark will end at:2015-07-24 09:03:10
----------Benchmark Statistics--------------
 Concurrents: 100
 ClientNums: 1
 RequestSize: 5120 bytes
 Runtime: 180 seconds
 Benchmark Time: 141
 Requests: 1715123 Success: 100% (1715123) Error: 0% (0)
 Avg TPS: 11585 Max TPS: 12336 Min TPS: 8872
 Avg RT: 8ms
 RT <= 0: 0% 0/1715123
 RT (0,1]: 0% 5/1715123
 RT (1,5]: 1% 25981/1715123
 RT (5,10]: 90% 1544705/1715123
 RT (10,50]: 8% 142412/1715123
 RT (50,100]: 0% 1919/1715123
 RT (100,500]: 0% 101/1715123
 RT (500,1000]: 0% 0/1715123
 RT > 1000: 0% 0/1715123

 2015-07-24 09:00:08 ready to start client benchmark,server is ,concurrents is: 100,clientNums is: 1,requestSize is:5120 bytes,the benchmark will end at:2015-07-24 09:03:08
 ----------Benchmark Statistics--------------
  Concurrents: 100
  ClientNums: 1
  RequestSize: 5120 bytes
  Runtime: 180 seconds
  Benchmark Time: 141
  Requests: 1664909 Success: 100% (1664909) Error: 0% (0)
  Avg TPS: 11314 Max TPS: 12153 Min TPS: 8626
  Avg RT: 8ms
  RT <= 0: 0% 0/1664909
  RT (0,1]: 0% 8/1664909
  RT (1,5]: 1% 20789/1664909
  RT (5,10]: 88% 1469456/1664909
  RT (10,50]: 10% 172007/1664909
  RT (50,100]: 0% 2458/1664909
  RT (100,500]: 0% 191/1664909
  RT (500,1000]: 0% 0/1664909
  RT > 1000: 0% 0/1664909

  2015-07-24 09:00:06 ready to start client benchmark,server is ,concurrents is: 100,clientNums is: 1,requestSize is:5120 bytes,the benchmark will end at:2015-07-24 09:03:06
  ----------Benchmark Statistics--------------
   Concurrents: 100
   ClientNums: 1
   RequestSize: 5120 bytes
   Runtime: 180 seconds
   Benchmark Time: 141
   Requests: 1672639 Success: 100% (1672639) Error: 0% (0)
   Avg TPS: 11324 Max TPS: 12265 Min TPS: 8786
   Avg RT: 8ms
   RT <= 0: 0% 0/1672639
   RT (0,1]: 0% 0/1672639
   RT (1,5]: 1% 24550/1672639
   RT (5,10]: 88% 1473907/1672639
   RT (10,50]: 10% 171682/1672639
   RT (50,100]: 0% 2300/1672639
   RT (100,500]: 0% 200/1672639
   RT (500,1000]: 0% 0/1672639
   RT > 1000: 0% 0/1672639

    8. 压测 10240字节 网络:1.42MB/s cpu:136% 内存:6.5  /cpu:139% 内存:12
    2015-07-24 09:05:20 ready to start client benchmark,server is ,concurrents is: 100,clientNums is: 1,requestSize is:10240 bytes,the benchmark will end at:2015-07-24 09:08:20
----------Benchmark Statistics--------------
 Concurrents: 100
 ClientNums: 1
 RequestSize: 10240 bytes
 Runtime: 180 seconds
 Benchmark Time: 141
 Requests: 846962 Success: 100% (846962) Error: 0% (0)
 Avg TPS: 5773 Max TPS: 6089 Min TPS: 5391
 Avg RT: 17ms
 RT <= 0: 0% 0/846962
 RT (0,1]: 0% 0/846962
 RT (1,5]: 0% 2337/846962
 RT (5,10]: 3% 29134/846962
 RT (10,50]: 96% 815491/846962
 RT (50,100]: 0% 0/846962
 RT (100,500]: 0% 0/846962
 RT (500,1000]: 0% 0/846962
 RT > 1000: 0% 0/846962

 5个客户端:压测 10240字节 网络:7.0MB/s cpu:590% 内存:6.6  /cpu:130%*5 内存:12*5

 2015-07-24 09:10:25 ready to start client benchmark,server is ,concurrents is: 100,clientNums is: 1,requestSize is:10240 bytes,the benchmark will end at:2015-07-24 09:13:25
----------Benchmark Statistics--------------
 Concurrents: 100
 ClientNums: 1
 RequestSize: 10240 bytes
 Runtime: 180 seconds
 Benchmark Time: 141
 Requests: 880699 Success: 100% (880699) Error: 0% (0)
 Avg TPS: 6029 Max TPS: 6289 Min TPS: 5656
 Avg RT: 16ms
 RT <= 0: 0% 0/880699
 RT (0,1]: 0% 0/880699
 RT (1,5]: 0% 170/880699
 RT (5,10]: 1% 9350/880699
 RT (10,50]: 98% 871047/880699
 RT (50,100]: 0% 132/880699
 RT (100,500]: 0% 0/880699
 RT (500,1000]: 0% 0/880699
 RT > 1000: 0% 0/880699

 2015-07-24 09:10:26 ready to start client benchmark,server is ,concurrents is: 100,clientNums is: 1,requestSize is:10240 bytes,the benchmark will end at:2015-07-24 09:13:26
----------Benchmark Statistics--------------
 Concurrents: 100
 ClientNums: 1
 RequestSize: 10240 bytes
 Runtime: 180 seconds
 Benchmark Time: 141
 Requests: 900808 Success: 100% (900808) Error: 0% (0)
 Avg TPS: 6154 Max TPS: 6394 Min TPS: 5743
 Avg RT: 16ms
 RT <= 0: 0% 0/900808
 RT (0,1]: 0% 0/900808
 RT (1,5]: 0% 150/900808
 RT (5,10]: 2% 18538/900808
 RT (10,50]: 97% 882117/900808
 RT (50,100]: 0% 3/900808
 RT (100,500]: 0% 0/900808
 RT (500,1000]: 0% 0/900808
 RT > 1000: 0% 0/900808

 2015-07-24 09:10:28 ready to start client benchmark,server is ,concurrents is: 100,clientNums is: 1,requestSize is:10240 bytes,the benchmark will end at:2015-07-24 09:13:28
 ----------Benchmark Statistics--------------
  Concurrents: 100
  ClientNums: 1
  RequestSize: 10240 bytes
  Runtime: 180 seconds
  Benchmark Time: 141
  Requests: 879813 Success: 100% (879813) Error: 0% (0)
  Avg TPS: 5969 Max TPS: 6221 Min TPS: 5551
  Avg RT: 16ms
  RT <= 0: 0% 0/879813
  RT (0,1]: 0% 0/879813
  RT (1,5]: 0% 111/879813
  RT (5,10]: 0% 7961/879813
  RT (10,50]: 99% 871630/879813
  RT (50,100]: 0% 111/879813
  RT (100,500]: 0% 0/879813
  RT (500,1000]: 0% 0/879813
  RT > 1000: 0% 0/879813

  2015-07-24 09:10:30 ready to start client benchmark,server is ,concurrents is: 100,clientNums is: 1,requestSize is:10240 bytes,the benchmark will end at:2015-07-24 09:13:30
----------Benchmark Statistics--------------
 Concurrents: 100
 ClientNums: 1
 RequestSize: 10240 bytes
 Runtime: 180 seconds
 Benchmark Time: 141
 Requests: 899934 Success: 100% (899934) Error: 0% (0)
 Avg TPS: 6107 Max TPS: 6331 Min TPS: 5883
 Avg RT: 16ms
 RT <= 0: 0% 0/899934
 RT (0,1]: 0% 0/899934
 RT (1,5]: 0% 98/899934
 RT (5,10]: 0% 7754/899934
 RT (10,50]: 99% 892004/899934
 RT (50,100]: 0% 78/899934
 RT (100,500]: 0% 0/899934
 RT (500,1000]: 0% 0/899934
 RT > 1000: 0% 0/899934

 2015-07-24 09:10:31 ready to start client benchmark,server is ,concurrents is: 100,clientNums is: 1,requestSize is:10240 bytes,the benchmark will end at:2015-07-24 09:13:31
 ----------Benchmark Statistics--------------
  Concurrents: 100
  ClientNums: 1
  RequestSize: 10240 bytes
  Runtime: 180 seconds
  Benchmark Time: 141
  Requests: 878404 Success: 100% (878404) Error: 0% (0)
  Avg TPS: 5956 Max TPS: 6185 Min TPS: 5551
  Avg RT: 16ms
  RT <= 0: 0% 0/878404
  RT (0,1]: 0% 0/878404
  RT (1,5]: 0% 188/878404
  RT (5,10]: 0% 7497/878404
  RT (10,50]: 99% 870613/878404
  RT (50,100]: 0% 106/878404
  RT (100,500]: 0% 0/878404
  RT (500,1000]: 0% 0/878404
  RT > 1000: 0% 0/878404
