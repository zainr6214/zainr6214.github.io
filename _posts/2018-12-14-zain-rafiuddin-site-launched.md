
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

(put-image white-stripe3 50 143 basle3)```




