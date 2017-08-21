# VPS-CLOUD-POROWNANIE


## SPEEDTEST

Każdy test wykonywany był 5 razy. Najlepszy wynik znajduje się w tableli.

**WAW_ORANGE**

Hosted by Orange Polska S.A. (Warsaw)

| X  | Download  | Upload |
| ------------- | ------------- | ------------- |
| do-cloud-fra1  | 121.95  | 1008.75 |
| dome-vps-olsztyn  | 36.31  | 203.46 |
| gc-cloud-west2 | 2041.15 | 739.92 |
| ovh-private-hostl-fr | 258.13 | 475.60 |
| ovh-public-c27-waw | 243.19 | 239.20 |

**WAW_NETIA**

Hosted by NETIA S.A. (Warsaw)

| X  | Download  | Upload |
| ------------- | ------------- | ------------- |
| do-cloud-fra1  | 604.99  | 449.47 |
| dome-vps-olsztyn  | 35.33  | 332.09 |
| gc-cloud-west2 | 2234.37 | 432.77 |
| ovh-private-hostl-fr | 307.58 | 349.02 |
| ovh-public-c27-waw | 244.34 | 231.84 |


**PARIS**

Hosted by Orange (Paris)

| X  | Download  | Upload |
| ------------- | ------------- | ------------- |
| do-cloud-fra1  | 74.75  | 87.81 |
| dome-vps-olsztyn  | 33.26 | 80.75 |
| gc-cloud-west2 | 842.59 |397.77 |
| ovh-private-hostl-fr |880.23 | 432.72 |
| ovh-public-c27-waw | 237.04 | 21.13 |

**LONDON**

Hosted by Vodafone UK

| X  | Download  | Upload |
| ------------- | ------------- | ------------- |
| do-cloud-fra1  | 379.29  | 166.43 |
| dome-vps-olsztyn  | 36.80 | 157.93 |
| gc-cloud-west2 | 2426.27 |1006.11  |
| ovh-private-hostl-fr | 490.25 | 157.77 |
| ovh-public-c27-waw | 225.93 | 113.27 |


## DD TEST
Każdy test z użyciem dd uruchamiany był 5razy. Wybrany został najlepszy wynik. 


**CPU TEST**
__dd if=/dev/zero bs=1M count=1024__

| X  | Time (s)  | Speed (MB/s) |
| ------------- | ------------- | ------------- |
| do-cloud-fra1  | 2.5641  | 419 |
| dome-vps-olsztyn  | 2.65952 | 404 |
| gc-cloud-west2 |2.26019  |475  |
| ovh-private-hostl-fr | 2,76387 | 388 |
| ovh-public-c27-waw | 2.03049 | 529 |



**IO TEST**
__dd if=/dev/zero of=test bs=64k count=16k conv=fdatasync__

| X  | Time  | Speed (MB/s) |
| ------------- | ------------- | ------------- |
| do-cloud-fra1  | 1.3962  | 769 |
| dome-vps-olsztyn  | 0.448955 | 2400 |
| gc-cloud-west2 | 7.76907  |138  |
| ovh-private-hostl-fr | 13,0323 | 82,4 |
| ovh-public-c27-waw | 2.64323 | 406 |
