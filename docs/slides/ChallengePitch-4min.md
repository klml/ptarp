---
title: P2P2P Logistics 
subtitle: Last Mile Logistics in Urban Areas
author: Klaus 'klml' Mueller
date: October 16, 2024
---

# What's my Problem

Too many courier vehicles drive the same streets, ring the same doors.


![](https://upload.wikimedia.org/wikipedia/commons/thumb/7/71/2malKurierdienst.JPG/1024px-2malKurierdienst.JPG)


# My role model: IP and BGP

Start an IP packet with M-Net, transported by Telekom and delivered by netCologne.  

## Internet Protocol

__137.7.137.7__


## Border Gateway Protocol

![](https://upload.wikimedia.org/wikipedia/commons/thumb/6/65/Bgp_rr.svg/320px-Bgp_rr.svg.png)

## This works

```
$ tracepath -4b netcologne.de
 1:  fritz.nas (192.168.178.1)                             2.276ms 
 2:  192.0.0.2 (192.0.0.2)                                 2.485ms pmtu 1452
 3:  ae3.rt-decix-4.m-online.net (82.135.16.175)          15.031ms asymm  8 
 4:  as8422.frankfurt.megaport.com (62.69.146.5)          15.850ms asymm  8 
 5:  ip-core-sto1-ae3.netcologne.de (81.173.192.113)      16.832ms asymm  8 
```


# My Idea

I want to hand over my parcel to DHL, gets transported by UPS and delivered from my pizza delivery guy,  brings me my lunch.


![](https://upload.wikimedia.org/wikipedia/commons/thumb/6/67/DPD_Pickup_Paketshop.jpg/320px-DPD_Pickup_Paketshop.jpg)
![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Right.svg/50px-Right.svg.png)
![](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2c/Samoch%C3%B3d_kuriera_holenderskiego_GLS_w_Tomaszowie_Mazowieckim.jpg/320px-Samoch%C3%B3d_kuriera_holenderskiego_GLS_w_Tomaszowie_Mazowieckim.jpg)
![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Right.svg/50px-Right.svg.png)
![](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/DPD_Kontrollraum-und-Linemaster.jpg/320px-DPD_Kontrollraum-und-Linemaster.jpg) 
![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Right.svg/50px-Right.svg.png)
![](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/BB79709_%2818.03.19%2C_Motorvej_501%2C_Viby_J%29DSC_3018_Balancer.jpg/320px-BB79709_%2818.03.19%2C_Motorvej_501%2C_Viby_J%29DSC_3018_Balancer.jpg)
![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Right.svg/50px-Right.svg.png)
![](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/DPD_Kontrollraum-und-Linemaster.jpg/320px-DPD_Kontrollraum-und-Linemaster.jpg) 
![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Right.svg/50px-Right.svg.png)
![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/cb/Bierlaster_von_Augustiner-Br%C3%A4u_in_M%C3%BCnchen.JPG/320px-Bierlaster_von_Augustiner-Br%C3%A4u_in_M%C3%BCnchen.JPG)
![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Right.svg/50px-Right.svg.png)
![](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ef/Parcels_crowded_near_the_gate_of_one_community_in_Suzhou-20201107.jpg/320px-Parcels_crowded_near_the_gate_of_one_community_in_Suzhou-20201107.jpg)
![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Right.svg/50px-Right.svg.png)
![](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f3/Delivery_vehicle_in_Peru.jpg/300px-Delivery_vehicle_in_Peru.jpg)
![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Right.svg/50px-Right.svg.png)
![](https://img.br.de/5a5762b6-027e-4953-9087-480196a23644.jpeg?q=85&rect=0%2C371%2C3809%2C2145&w=420)
![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Right.svg/50px-Right.svg.png)
![](https://upload.wikimedia.org/wikipedia/commons/thumb/3/34/LongJohn11b.jpg/320px-LongJohn11b.jpg)



# Exists

__137.7.137.7__ ==> ![](https://upload.wikimedia.org/wikipedia/commons/thumb/d/df/Paketaufkleber_DHL-Paket_mit_Paketmarke_bis_31%2C5_kg-2016.jpg/320px-Paketaufkleber_DHL-Paket_mit_Paketmarke_bis_31%2C5_kg-2016.jpg)


![](https://upload.wikimedia.org/wikipedia/commons/thumb/6/65/Bgp_rr.svg/320px-Bgp_rr.svg.png)==> __????__


[München eröffnet Radlogistik-Hub](https://www.br.de/nachrichten/bayern/4-000-autofahrten-weniger-muenchen-eroeffnet-radlogistik-hub,Tlnbiyo) 
![](https://img.br.de/5a5762b6-027e-4953-9087-480196a23644.jpeg?q=85&rect=0%2C371%2C3809%2C2145&w=420)

