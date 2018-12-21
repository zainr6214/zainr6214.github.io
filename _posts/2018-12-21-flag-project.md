
---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of greece by Zain R

## Describe your program

-  The country flag that i did was the flag of greece
-  I believe that this flag project deserves a grade of 2

<!--- Delete this comment and add your writing -->

## Current output

-   Insert an image that your program currently produces. _then delete this instruction_

* * *
![WeScheme](/images/6.png)
* * *

## Describe your process.

- some questions that i had would be how to find a common factor for every number that was in the flag in order to make the scaling of the flag work as well as if that was necessary. A piece of information that a class mate gave me was to create a size defintion and to multiply the numbers by it.The teacher also gave me a work sheet with an ex
<!--- Delete this comment and add your writing -->


## Explain your code.


-The first 5 lines are all definitions for the width,hieght,size,ad the measurments for the white stripes that will be used for the flag of greece.The nest 5 lines would be puting most of the flag together in the correct positon an all of the numbers that are usedin this program for either its measuments or location of the flag are all multiplied by the size defintion
-  each of these lines of code function indipendantly by either giving a measurment that can be used or creating a specific a specific shape of the flag of greece. 
* * *

```
(define size  3 )



(define width (* size 300))
(define height (* size 200.))
(define white-stripe (  rectangle (* width 1) ( * height 1/9)"solid" "white"))
(define base (rectangle width height "solid" "blue"))


(define stripe-base(put-image white-stripe (* size 150) (* size 164) (put-image  white-stripe (* size 150) (* size 120) (put-image white-stripe (* size 150) (* size 76)(put-image white-stripe (* size 150) (* size 32)
(rectangle width height "solid" "blue"))))))


(define canton (square ( * width 1/3) "solid" "blue"))

```

* * *


<!--- Delete this comment and add your writing -->


.2## Program code

```
(define size  3 )

(define width (* size 300))
(define height (ctangle 300 200 "outline" "black"))(put-image (rotate 180 (triangle 50 "outline" "blue")) 150 90 (recta* size 200.))
(define white-stripe (  rectangle (* width 1) ( * height 1/9)"solid" "white"))
(define base (rectangle width height "solid" "blue"))


(define stripe-base(put-image white-stripe (* size 150) (* size 164) (put-image  white-stripe (* size 150) (* size 120) (put-image white-stripe (* size 150) (* size 76)(put-image white-stripe (* size 150) (* size 32)
(rectangle width height "solid" "blue"))))))


(define canton (square ( * width 1/3) "solid" "blue"))


(define base2(put-image canton (* size 50) (* size 150) stripe-base ) )

(define white-stripe2 (rectangle (* width 1/3 )(* size 22) "solid" "white"))

(define base3(put-image white-stripe2 (* size 50)(* size  142) base2))

(define white-stripe3 (rectangle (* height 1/9) (* height 6/9) "solid" "white"))

(define greece (put-image white-stripe3 (* size 50) (* size 142.5) base3))

 
greece





```
