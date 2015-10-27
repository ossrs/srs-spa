# srs-spa

The SPA(Stream Player for Android) play live stream from SRS over HTTP-FLV. 

Please use [ExoPlayer](https://github.com/google/ExoPlayer), which will support FLV in 1.6+, read [patch](https://github.com/google/ExoPlayer/pull/828).

## HTTP-TS

Publish HTTP-FLV and play HTTP-TS is ok~

I test the latency, use srs-sea to publish and exoplayer to play, the latency is 1s - 3s:
![sea exoplayer](https://cloud.githubusercontent.com/assets/2777660/10747895/7655950a-7c95-11e5-92ad-40e4037b9035.jpg)


## Links

Projects from SRS-ORG:

* SRS: https://github.com/simple-rtmp-server/srs
* SRS-BLE(pc encoder): https://github.com/simple-rtmp-server/srs-ble
* SRS-SEA(android encoder): https://github.com/simple-rtmp-server/srs-sea
* SRS-SPA(player): https://github.com/simple-rtmp-server/srs-spa
* SRS-DOCKER: https://github.com/simple-rtmp-server/srs-docker

Winlin 2015.5
