![XNT](https://github.com/gokyuzugokturk/igotek-xnt/blob/main/img/image.png)

Neptune Privacy XNT Miner v1.1 for HIVEOS

All NVIDIA graphic cards are supported !

Video Tutorial: https://youtu.be/rpcNwmAC7H8  
Discord: https://discord.gg/w6GuBsWHQa

*****

HIVEOS: WALLET CREATION  
![wallet](https://github.com/gokyuzugokturk/igotek-xnt/blob/main/img/001.png)

Get wallet address from https://safetrade.com  
Dont enter your wallet address here.  
Set wallet address at the flight sheet !

*****

HIVEOS: FLIGHT SHEET  
![flighsheet](https://github.com/gokyuzugokturk/igotek-xnt/blob/main/img/002.png)

*****

HIVEOS: FLIGHT SHEET  
![flighsheet](https://github.com/gokyuzugokturk/igotek-xnt/blob/main/img/003.png)

Wallet and worker template: %WAL%  

Installation URL: https://github.com/gokyuzugokturk/igotek-xnt-miner/releases/download/v1.0/xnt-1.0.tar.gz  

Pool URL: stratum+ssl://eu.poolhub.io:30111

Extra config arguments: --neptunewallet YOUR-WALLET-ADDRESS

This miner is for Neptune Privacy XTN !  
Use XTN wallet address. Neptune Privacy (XTN) 

This miner is not for Neptune Cash NPT !  
Dont use NPT wallet address. Neptune Cash (NPT)  

*****

BENCHMARKS

You can set overclock settings depends on your graphic card.   
Just try this ones as start and find the proper settings for your graphic cards.

RTX5090: 40MH/s NO OC, NO PL LIMIT  
RTX4090: 31MH/s @ 450PL NO OC, 15.2MH/s @ 400PL NO OC, 14.8MH/s @ 370PL NO OC, 12MH/s @ 350PL NO OC

RTX3090 > 13.85MH/s @ 300W  
Core Offset 150, Core Clock 1710, Lock Memory Clock 5000  
![RTX3090](https://github.com/gokyuzugokturk/igotek-xnt/blob/main/img/004.png)

RTX3080Ti > 13.50MH/s @ 270W  
Core Offset 150, Core Clock 1710, Lock Memory Clock 5000  
![RTX3080Ti](https://github.com/gokyuzugokturk/igotek-xnt/blob/main/img/005.png)

RTX3080 > 10.30MH/s @ 235W  
Core Offset 150, Core Clock 1710, Lock Memory Clock 5000  
![RTX3080](https://github.com/gokyuzugokturk/igotek-xnt/blob/main/img/006.png)

RTX3070 > 7.05MH/s @ 125W  
Core Offset 200, Core Clock 1710, Lock Memory Clock 5000  
![RTX3070](https://github.com/gokyuzugokturk/igotek-xnt/blob/main/img/007.png)

RTX3060Ti > 5.80MH/s @ 115W  
Core Offset 150, Core Clock 1710, Lock Memory Clock 5000  
![RTX3060Ti](https://github.com/gokyuzugokturk/igotek-xnt/blob/main/img/008.png)

RTX3060 > 4.70MH/s @ 115W  
Core Offset 150, Core Clock 1710, Lock Memory Clock 5000  
![RTX3060](https://github.com/gokyuzugokturk/igotek-xnt/blob/main/img/009.png)

RTXA4000 > 7.50MH/s @ 120W  
Core Offset 150, Core Clock 1710, Lock Memory Clock 5000  
![RTXA4000](https://github.com/gokyuzugokturk/igotek-xnt/blob/main/img/010.png)

RTX4080 > 20.80MH/s @ 280W  
Core Offset 200, Core Clock 2655, Lock Memory Clock 5000  
![RTXA4000](https://github.com/gokyuzugokturk/igotek-xnt/blob/main/img/RTX4080.png)

RTX4070Ti > 16.65MH/s @ 230W  
Core Offset 200, Core Clock 2600, Lock Memory Clock 5000  
![RTX4070Ti](https://github.com/gokyuzugokturk/igotek-xnt/blob/main/img/RTX4070Ti.webp)

RTX3070 Laptop > 6.10MH/s @ 85W  
Core Offset 150, Core Clock 1710, Lock Memory Clock 5000  
![RTX3070-Laptop](https://github.com/gokyuzugokturk/igotek-xnt/blob/main/img/RTX3070-Laptop.webp)

RTX3080 LAptop > 7.35MH/s @ 100W  
Core Offset 150, Core Clock 1710, Lock Memory Clock 5000  
![RTX3080-Laptop](https://github.com/gokyuzugokturk/igotek-xnt/blob/main/img/RTX3080-Laptop.webp)

*****

Error Reporting:

Just lower Lock Core Clock value to lower if you see this error.  
You must enter 15 value lower.  
Example: set 1695 instead of 1710  
Example: set 1680 instead of 1695
![error](https://github.com/gokyuzugokturk/igotek-xnt/blob/main/img/error.png)

Sometimes, you can see your rig uses too lower power than usual, but the hashrates are good. that is an error.
You must lower Lock Core Clock to a lower value (-15) and reboot the rig to fix that error.

Poolhub.io url cannot be accesible at some locations. This is because your internet server provider. There are people who can access the pool by using VPN. I cannot help you about VPN usage. You need to search for using VPN over HiveOS. Just go Discord if you have any problem to access to the pool. I can check it for you. Usually, there are another problems at the rigs. Mostly, I fix the problems by updating the rig, flighsheet, overclock settings.

NVIDIA OC failed  
SET POWER LIMIT: 115.0 W [Not Supported]  
You can see this error if you use Laptop GPUs. No problem, you can set overclocks except PL. Just dismiss the error.

*****

Dev + Pool Fee: %10  
Auto Pool Payout: 50 XNT

*****

GPU Selection at the extra config: --gpu 0,1,2,3,4,5

*****

I m not the owner of the poolhub.io + I m not the developer of OXZD-0.7.5 + All fees goes to its developer ! The idle-time is on my hands. But you can set idle-time for your own choice ! You can edit the files, no restrictions. Just dont use the miner if you dont like it. Use it your own risk.

*****

![pool](https://github.com/gokyuzugokturk/igotek-xnt/blob/main/img/pool_001.png)

![pool](https://github.com/gokyuzugokturk/igotek-xnt/blob/main/img/pool_002.png)

