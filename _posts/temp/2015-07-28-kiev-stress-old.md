机器:
1. 100byte 8.0MB/S   server:459 0.6 - client:234 8.5

Concurrents: 100
ClientNums: 1
RequestSize: 100 bytes
Runtime: 120 seconds
Benchmark Time: 81
Requests: 3349304 Success: 99% (3346858) Error: 0% (2446)
Avg TPS: 37563 Max TPS: 50977 Min TPS: 5626
Avg RT: 2ms
RT <= 0: 0% 1374/3349304
RT (0,1]: 10% 344478/3349304
RT (1,5]: 89% 2999274/3349304
RT (5,10]: 0% 200/3349304
RT (10,50]: 0% 1208/3349304
RT (50,100]: 0% 0/3349304
RT (100,500]: 0% 2249/3349304
RT (500,1000]: 0% 518/3349304
RT > 1000: 0% 3/3349304

Concurrents: 100
ClientNums: 1
RequestSize: 100 bytes
Runtime: 120 seconds
Benchmark Time: 81
Requests: 3635864 Success: 99% (3633267) Error: 0% (2597)
Avg TPS: 41162 Max TPS: 59597 Min TPS: 4049
Avg RT: 2ms
RT <= 0: 0% 6547/3635864
RT (0,1]: 19% 710431/3635864
RT (1,5]: 80% 2914577/3635864
RT (5,10]: 0% 352/3635864
RT (10,50]: 0% 992/3635864
RT (50,100]: 0% 0/3635864
RT (100,500]: 0% 2365/3635864
RT (500,1000]: 0% 600/3635864
RT > 1000: 0% 0/3635864

Concurrents: 100
ClientNums: 1
RequestSize: 100 bytes
Runtime: 120 seconds
Benchmark Time: 81
Requests: 3483403 Success: 99% (3480548) Error: 0% (2855)
Avg TPS: 39636 Max TPS: 57911 Min TPS: 8078
Avg RT: 2ms
RT <= 0: 0% 3425/3483403
RT (0,1]: 15% 530472/3483403
RT (1,5]: 84% 2945132/3483403
RT (5,10]: 0% 235/3483403
RT (10,50]: 0% 937/3483403
RT (50,100]: 0% 53/3483403
RT (100,500]: 0% 2549/3483403
RT (500,1000]: 0% 599/3483403
RT > 1000: 0% 1/3483403

1. 500byte 7.4MB/S   server:255 5.3 - client:228 8.5

Concurrents: 100
ClientNums: 1
RequestSize: 500 bytes
Runtime: 120 seconds
Benchmark Time: 81
Requests: 3634914 Success: 99% (3632365) Error: 0% (2549)
Avg TPS: 41225 Max TPS: 57163 Min TPS: 4274
Avg RT: 2ms
RT <= 0: 0% 3278/3634914
RT (0,1]: 16% 598171/3634914
RT (1,5]: 83% 3029387/3634914
RT (5,10]: 0% 86/3634914
RT (10,50]: 0% 1082/3634914
RT (50,100]: 0% 47/3634914
RT (100,500]: 0% 2263/3634914
RT (500,1000]: 0% 599/3634914
RT > 1000: 0% 1/3634914


2. 5个客户端
server 540 725 跳动 8.7  160*5 5.4*5
15-18MB/s

Concurrents: 100
 ClientNums: 1
 RequestSize: 10200 bytes
 Runtime: 120 seconds
 Benchmark Time: 81
 Requests: 1921406 Success: 99% (1917141) Error: 0% (4265)
 Avg TPS: 21839 Max TPS: 31471 Min TPS: 898
 Avg RT: 4ms
 RT <= 0: 0% 50/1921406
 RT (0,1]: 4% 77074/1921406
 RT (1,5]: 83% 1595552/1921406
 RT (5,10]: 11% 223567/1921406
 RT (10,50]: 1% 19421/1921406
 RT (50,100]: 0% 285/1921406
 RT (100,500]: 0% 5138/1921406
 RT (500,1000]: 0% 217/1921406
 RT > 1000: 0% 102/1921406

 Concurrents: 100
ClientNums: 1
RequestSize: 10200 bytes
Runtime: 120 seconds
Benchmark Time: 81
Requests: 1906621 Success: 99% (1902348) Error: 0% (4273)
Avg TPS: 21589 Max TPS: 31625 Min TPS: 1857
Avg RT: 4ms
RT <= 0: 0% 61/1906621
RT (0,1]: 4% 88945/1906621
RT (1,5]: 82% 1563551/1906621
RT (5,10]: 12% 229592/1906621
RT (10,50]: 0% 18704/1906621
RT (50,100]: 0% 179/1906621
RT (100,500]: 0% 5282/1906621
RT (500,1000]: 0% 107/1906621
RT > 1000: 0% 200/1906621

----------Benchmark Statistics--------------
 Concurrents: 100
 ClientNums: 1
 RequestSize: 10200 bytes
 Runtime: 120 seconds
 Benchmark Time: 81
 Requests: 1932872 Success: 99% (1928348) Error: 0% (4524)
 Avg TPS: 22103 Max TPS: 33749 Min TPS: 727
 Avg RT: 4ms
 RT <= 0: 0% 396/1932872
 RT (0,1]: 5% 105334/1932872
 RT (1,5]: 82% 1585517/1932872
 RT (5,10]: 11% 217241/1932872
 RT (10,50]: 0% 18485/1932872
 RT (50,100]: 0% 103/1932872
 RT (100,500]: 0% 5561/1932872
 RT (500,1000]: 0% 135/1932872
 RT > 1000: 0% 100/1932872

 ---------Benchmark Statistics--------------
 Concurrents: 100
 ClientNums: 1
 RequestSize: 10200 bytes
 Runtime: 120 seconds
 Benchmark Time: 81
 Requests: 1933244 Success: 99% (1928625) Error: 0% (4619)
 Avg TPS: 21821 Max TPS: 31803 Min TPS: 2334
 Avg RT: 4ms
 RT <= 0: 0% 236/1933244
 RT (0,1]: 5% 107370/1933244
 RT (1,5]: 82% 1586091/1933244
 RT (5,10]: 10% 210919/1933244
 RT (10,50]: 1% 22616/1933244
 RT (50,100]: 0% 177/1933244
 RT (100,500]: 0% 5535/1933244
 RT (500,1000]: 0% 291/1933244
 RT > 1000: 0% 9/1933244


 ----------Benchmark Statistics--------------
  Concurrents: 100
  ClientNums: 1
  RequestSize: 10200 bytes
  Runtime: 120 seconds
  Benchmark Time: 81
  Requests: 1898247 Success: 99% (1893326) Error: 0% (4921)
  Avg TPS: 21469 Max TPS: 31034 Min TPS: 2923
  Avg RT: 4ms
  RT <= 0: 0% 1109/1898247
  RT (0,1]: 5% 108400/1898247
  RT (1,5]: 81% 1547948/1898247
  RT (5,10]: 11% 213778/1898247
  RT (10,50]: 1% 20808/1898247
  RT (50,100]: 0% 171/1898247
  RT (100,500]: 0% 5831/1898247
  RT (500,1000]: 0% 200/1898247
  RT > 1000: 0% 2/1898247
