# Allowed restricted apks list

This repo create for 3X-UI panel Subscription settings by https://github.com/MHSanaei/3x-ui project.

# How to apply list

## Happ

In this screenshot we have 3X-UI interface and we should go to **Subscription** in Burger menu, then go to **Happ**.

<p align="center"><img src="./images/1.jpg"/></p>

After going to, go to **Network & TUN engine** tab and scroll down to **Android Package Names** and set **Android Per-App Proxy Mode** to **On (Proxy Only Listed Apps)**.

<p align="left"><img src="./images/2.jpg"/></p>

<p align="right"><img src="./images/3.jpg"/></p>

After that, paste the link to **Android Package Names** https://raw.githubusercontent.com/linuxuzver/allowed-restricted-apks-list/refs/heads/main/prepared_happ.txt link.

<p align="center"><img src="./images/4.jpg"/></p>

> [!NOTE]
> I have not tested yet, but if you encountered an errors or something, just copy & paste **prepared_happ.txt** contents directly to prompt.

## Incy

In this screenshot go to **Incy** tab.

<p align="center"><img src="./images/5.jpg"/></p>

After going to, go to **Privacy** tab and scroll down to **App list**, set **Per-app mode type** to **Only listed apps** and paste
https://raw.githubusercontent.com/linuxuzver/allowed-restricted-apks-list/refs/heads/main/list.txt to prompt.

<p align="center"><img src="./images/6.jpg"/></p>

# Contribution

## Happ

Update **list.txt** with **./PREPARE_HAPP** script, then it will update to comma-separated file **prepared_happ.txt**.

## Incy

Just edit **list.txt** and pull request changes.
