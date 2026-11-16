# Allowed restricted apks list
This repo create for 3X-UI panel Subscription settings by [](https://github.com/MHSanaei/3x-ui).
# How to apply list
* *Happ*
  In this screenshot we have 3X-UI interface and we should go to `Subscription` in Burger menu, then go to `Happ`.
  [](./images/1.jpg)
  After going to, go to `Network & TUN engine` tab and scroll down to `Android Package Names` and set `Android Per-App Proxy Mode` to `On (Proxy Only Listed Apps)`.
  [](./images/2.jpg) [](./images/3.jpg)
  After that, paste the link to `Android Package Names` [](https://raw.githubusercontent.com/linuxuzver/allowed-restricted-apks-list/prepared_happ.txt).
  [](./images/4.jpg)
  > [!NOTE]
  > I have not tested yet, but if you encountered an errors or something, just copy & paste `prepared_happ.txt` contents directly to prompt.
* *Incy*
  In this screenshot go to `Incy` tab.
  [](./images/5.jpg)
  After going to, go to `Privacy` tab and scroll down to `App list`, set `Per-app mode type` to `Only listed apps` and paste [](https://raw.githubusercontent.com/linuxuzver/allowed-restricted-apks-list/list.txt) to prompt.
  [](./images/6.jpg)
# Contribution
If you want to contribute to the applist, you should do these steps:
* Write an apk to list;
* *Happ*
Update `list.txt` with `./PREPARE_HAPP` script (thanks to [](https://stackoverflow.com/a/1252191)), then it will update to comma-separated file `prepared_happ.txt`.
* *Incy*
Just edit `list.txt` and pull request changes.
