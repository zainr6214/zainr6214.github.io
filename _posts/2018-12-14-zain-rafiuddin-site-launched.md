
---
layout: post
title: "flag project-in progress"
date: 2018-12-14
---

This weeks blog post is focused around our flag projects wich ar currently incomplete.The flag that i will be completing on weshceme is the flag of greece and my present code is below

```(define width 300)
(define height 200)
(define white-stripe (rectangle 300 22 "solid" "white"))
(define base (rectangle width height "solid" "blue"))


(define stripe-base(put-image white-stripe 150 164 (put-image  white-stripe 150 120 (put-image white-stripe 150 76(put-image white-stripe 150 32
(rectangle width height "solid" "blue"))))))


(define canton (square 110 "solid" "blue"))


(define base2(put-image canton 50 150 stripe-base) )

(define white-stripe2 (rectangle 110 22 "solid" "white"))

(define base3(put-image white-stripe2 50 143 base2))

(define white-stripe3 (rectangle 22 110 "solid" "white"))

(put-image white-stripe3 50 143 basle3)
```

This program while it does show the image of a greece flag it is not yet sclalable becuase i dont yet have a size defention for the program. When i define size i can make it so that all the measurments of the flag are multiplyed by the size including the hieght an width as well as the placement of the stripes. Some challanges that i faced would be that i rewrote information that i could have defined and made more simple. This led to simple mistakes being difficult to fix.A question i would have is how to controle placment of the flag stripes by scaleing it down.An oppertunity would be that mr allata showed parts of the flag that could be defined for example the stripes measurments were all iddentical so i could simply define it as a stripe instead of writing the whole function.

This is the actual output that the program above gave me

