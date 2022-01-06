## Hız testi gerçekleştirmek için hazırlanmış basit konteyner uygulaması

___
## Proje linki: https://github.com/sivel/speedtest-cli
___

Docker konteyner olarak kullanımı:

```
docker run --rm techakademi/hiztest:1
```

```
Retrieving speedtest.net configuration...
Testing from Turkcell Superonline (213.**.**.**)...
Retrieving speedtest.net server list...
Selecting best server based on ping...
Hosted by ************* (İzmir) [11.22 km]: 54.993 ms
<<<<<<< HEAD
Testing download speed..................................................................
Download: 17.72 Mbit/s
Testing upload speed....................................................................
=======
Testing download speed.....................................................
Download: 17.72 Mbit/s
Testing upload speed.......................................................
>>>>>>> 56c83e19eab358f335bd96885cdf5ddcc97e1fdb
Upload: 18.15 Mbit/s
```


