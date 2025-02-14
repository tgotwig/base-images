# base-images

| Image                                         | OS  | Additions | CMD |
| :--                                           | :-- | :--       | --- |
| [alpine](https://github.com/tgotwig/alpine)   | alpine 3.21 | curl, fish, starship, zoxide | docker run -it --rm tgotwig/alpine |
| [node](https://github.com/tgotwig/node)       | alpine 3.21 | fish, starship, zoxide | docker run -it --rm tgotwig/node fish |
| [ubuntu](https://github.com/tgotwig/ubuntu)   | ubuntu 24.04 | curl, dnsutils (delv, dig, host, nslookup), fish, iproute2 (bridge, ctstat, ip, lnstat, nstat, rtmon, ss, tc), nc, nmap, ping, starship, z | docker run -it --rm tgotwig/ubuntu |
