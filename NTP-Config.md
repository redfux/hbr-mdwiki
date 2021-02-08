---
tags: [cisco, hp, Notebooks/Hersteller, ntp, switching]
title: NTP-Config
created: '2019-11-26T09:30:03.159Z'
modified: '2020-09-10T15:15:46.196Z'
---

# NTP-Config

## Cisco

    clock timezone MET 1
    clock summer-time MEST recurring last Sun Mar 2:00 last Sun Oct 3:00
    !
    ntp server 141.40.103.102
    ntp server 213.239.211.122

## HP ProCurve

    time timezone 60
    time daylight-time-rule Western-Europe
    sntp server 141.40.103.102
    sntp server 213.239.211.122
    timesync sntp
    sntp unicast
    sntp 720
