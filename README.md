# kitematic-hello-world-nginx

```
sudo docker history -H --no-trunc=true {imageid}

fa9a3bb406d3a73414ec8da7ba755799fa70df909e9295da468cd8615e66b919   8 weeks ago         /bin/sh -c #(nop) CMD ["sh" "/start.sh"]                                                                                      0 B                 
fa8fefb0eeccc8e9ff15966f8f0e10246edd8b52247e8f5fcc56acd313071ee1   8 weeks ago         /bin/sh -c #(nop) EXPOSE 80/tcp                                                                                               0 B                 
fc3c122e2641519de26421990aa2c05552c0069b31b60842bf86e18bf56694eb   8 weeks ago         /bin/sh -c #(nop) VOLUME [/website_files]                                                                                     0 B                 
df781af04f51b3fae64aaa57e6b1a1e77178b58f03a56c1aca3f881cfc178eb6   8 weeks ago         /bin/sh -c #(nop) ADD file:b7622ba85d90da3a0ea9b3d7bceb5f87de97a58c196b42e5d5619a50adbcc677 in /index.html                    475 B               
99b3ac4b2eccd28c95051bf6948748647e86f5d9b80be71c633e6c05233b4d8d   8 weeks ago         /bin/sh -c #(nop) ADD file:080ad5f813a3fa7078da5fb6f6b1b908c68769c514343063749b47858f1b4d3c in /start.sh                      222 B               
97f9de5b46016abf345eba71595826991c499495e4f7674924ec5cbd8ab17f3a   8 weeks ago         /bin/sh -c #(nop) ADD file:9679cdc31148907fc20098891250286b3c7987bfe33d2d8f62470f1f0c2675d3 in /etc/nginx/nginx.conf          762 B               
2e646a716c11e2e6fa54c6433baf7b33838ea5febe4fd11924ae2aebf820b2ac   8 weeks ago         /bin/sh -c mkdir /var/lib/nginx                                                                                               0 B                 
5888470cecdfb831b1f38b45784cc63469895362bfa6b0147d02f61a8cb7697b   8 weeks ago         /bin/sh -c opkg-install nginx                                                                                                 3.118 MB            
e015d7d3cb2daa4158ebd08892b6fa9c35c52e599f5daa8ab7039368326766ab   8 weeks ago         /bin/sh -c opkg-cl install http://downloads.openwrt.org/snapshots/trunk/x86/64/packages/base/libc_0.9.33.2-1_x86_64.ipk       445.6 kB            
0fa122787541b25686c9189575bd606405f09256064b77f5f764724020117124   8 weeks ago         /bin/sh -c opkg-cl install http://downloads.openwrt.org/snapshots/trunk/x86/64/packages/base/libgcc_4.8-linaro-1_x86_64.ipk   69.33 kB            
72d0fb19f9f70dd2cea3c2210bfa3ccdbf7c7839e6253d506df1aa07b6b8c9bb   8 weeks ago         /bin/sh -c #(nop) ADD file:89431bd7949be577f4f715c81592b5590f2cd88868f458dbfde33278a5fb4de1 in /lib/functions.sh              9.15 kB             
fc986ab7f61ec67dd53750edea526eb00a8f35fc7f7a01244b8ddba8421be170   8 weeks ago         /bin/sh -c #(nop) ADD file:5fbe3f3e6862d6d7f1557f86adc765a5288aee31250284ebd0ddc8fa32a01ae5 in /usr/bin/opkg-install          103 B               
c625faf066a6043a41c3e7894e3c4c31b50246ee8b70be59af96480cb69389e1   8 weeks ago         /bin/sh -c #(nop) ADD file:57b20209fd1127ebdba86c012d74c6c1e13ca5f6e0bb5e50c7d0734f4c1d3612 in /etc/opkg.conf                 221 B               
4a130ef69fe4c11804103d017eecb3af8845c7f3fcf089a2b168a5bf41c12163   8 weeks ago         /bin/sh -c #(nop) ADD file:b658245df0f835004836bdff5dae4879e7c3c59198ba18fa6f820b8e84681217 in /                              4.268 MB            

```
