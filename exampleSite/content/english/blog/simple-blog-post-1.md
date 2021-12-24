---
title: Downsizing problem using decision models
date: 2021-11-12T07:52:36+00:00
image_webp: "/images/ezgif-5-fd5c35c5c4.webp"
image: "/images/ezgif-5-fd5c35c5c4.webp"
author: Lakshya Sangar
description: This is meta description

---
Downsizing is a process of eliminating or decreasing the capacity of a service or a product by a company in order to optimise profits and minimise company resources put to use. Our problem situation considers an example where a company has to choose which product to eliminate in order to minimise storage capacity while keeping high value products in place, among other constraints.

The inventory of our problem statement consists of gadgets such as laptops, printers and tablets of different brands. Some of these gadgets promise high profits from retail, therefore much be restocked in the inventory, while others must get liquidated. The constraints attached with our problem situation regarding the cadets to be restocked are given below :

* At least 19 products will be eliminated.
* No more than £190,000 can be spent to restock all the products kept.
* The products kept should use no more than 180 square metres of space in total.
* If any Acer or any Asus computer is to be kept, then Epson printers will also be kept.
* If one product of a certain brand is eliminated, then all the products of that brand should be eliminated.
* At least five different tablet models need to be kept.
* At least three different laptop models need to be kept.
* If any desktops are to be kept, then at least three different monitor models will also be kept.

  These constraints are represented numerically in a table below :

![](/images/screenshot-2021-12-24-at-14-18-12.png)

> The aim is to minimise the liquidation cost, while respecting all the constraints.

Using excel solver to input the constraints given in the table while keeping the objective function to minimise the cost of liquidation, we get the solution.

![](/images/screenshot-2021-12-24-at-14-22-34.png)

Therefore, we can now follow the solution table to check which items need to be restocked and the rest can be liquidated, resulting in the most optimal solution.

Excel solver is excellent in optimising linear and binary problems to give the most optimal solutions which can help businesses make insight-based decisions.