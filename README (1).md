

## Methods

```sh
  [Layer 7]
 - cfb     | Bypass CF attack
 - pxcfb   | Bypass CF attack with proxy
 - cfreq   | Bypass CF UAM, CAPTCHA, BFM, etc,, with request
 - cfsoc   | Bypass CF UAM, CAPTCHA, BFM, etc,, with socket
 - pxsky   | Bypass Google Project Shield, Vshield, DDoS Guard Free, CF NoSec With Proxy
 - sky     | Sky method without proxy
 - http2   | HTTP 2.0 Request Attack 
 = pxhttp2 | HTTP 2.0 Request Attack With Proxy
 - spoof   | Spoof Attasck
 - pxspoof | Spoof Attack with Proxy
 - get     | Get  Request Attack
 - post    | Post Request Attack
 - head    | Head Request Attack
 - soc     | Socket Attack
 - pxraw   | Proxy Request Attack
 - pxsoc   | Proxy Socket Attack
 
  [Layer 4]
  -udp     | UDP Attack
  -tcp     | TCP Attack
  
  [Tools]
 - Dns     | Classic DNS Lookup
 - Geoip   | Geo IP Address Lookup
 - Subnet  | Subnet IP Address Lookup
```

## Videos
[![](https://user-images.githubusercontent.com/87601386/161339371-b6dfaa8f-1cf2-41d1-85c1-d82cdd98def1.png)](https://www.youtube.com/watch?v=MPKdfhPeLeE)

## hướng dẫn setup 
```sh
git clone https://github.com/Huythieu/ddosht
cd ddosht
pip3 install -r requirements.txt 
python3 setup.py
```

## hướng dẫn sử dụng
```sh
cd ddosht
```

```sh
python main.py
```

```sh
help
```

```sh
layer7
```

```sh
cfb
```
```sh
URL nhập link web cần ddos vd: https://huydznhat.com
THREAD : ae để bao nhiêu cũng đc miễn máy khỏe ae nên để 10000
TIME: thời gian tính bằng giây để bao nhiêu cũng đc
```
