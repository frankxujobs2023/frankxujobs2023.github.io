---
title: "Newsvendor Problem"
mathjax: true
layout: post
categories: media
---

The **newsvendor problem** or newsvendor inventory problem is a classic problem in operations
management, supply chain and applied economics. There are many variants of newsvendor
problem with the situation faced by a business owner who must decide how many daily orders
to stock in the face of uncertain demand and knowing that unsold products will be worthless or
at least require inventory cost at the end of the day. The business owner needs to decide a
sequence of daily orders to maximize the profits based on the observable data such as daily
sales and daily inventory, etc. 
> The newsvendor problem is an important problem in supply chain management and inventory control because 
> it represents a fundamental trade-off between the costs of overstocking and understocking in the face of 
> uncertain demand. This problem arises in many different contexts and industries, and finding an optimal solution 
> to the newsvendor problem can result in significant cost savings and revenue increases.


## 1. What is Newsvendor Problem?
In general, the newsvendor problem can be formulated as follows: a vendor has a fixed order cost to purchase a certain 
quantity of a product from a supplier, and a known selling price for the product. 
The vendor also knows the demand distribution for the product, but does not know the actual demand that will occur. 
The goal of the vendor is to determine the optimal order quantity that maximizes their expected profit.

The problem can be mathematically represented as a one-period decision problem under uncertainty. 
The vendor must balance the cost of overstocking (i.e. having excess inventory that does not get sold and incurs holding costs) 
with the cost of understocking (i.e. not having enough inventory to meet customer demand and losing potential sales).

The newsvendor problem has many practical applications beyond newspaper vending, 
such as managing inventories of perishable goods, managing supply chains with uncertain demand, 
and managing production capacity for custom-made products.

## 2. Why Newsvendor Problem is Important in Supply Chain?
The newsvendor problem is an important problem in supply chain management because it represents a fundamental 
trade-off that businesses face in managing their inventory: balancing the cost of understocking with the cost of overstocking.

In many supply chain contexts, the cost of understocking can be high. 
If a business does not have enough inventory to meet customer demand, they risk losing potential sales and damaging their reputation. 
On the other hand, the cost of overstocking can also be high, as excess inventory ties up working capital 
and incurs holding costs such as storage, insurance, and obsolescence.

The newsvendor problem provides a framework for businesses to optimize their inventory management 
by finding the optimal order quantity that maximizes their expected profit. 
By understanding the trade-off between understocking and overstocking, 
businesses can make informed decisions about how much inventory to order and when to order it.

The problem is also important because it represents a one-period decision problem under uncertainty, 
which is a common scenario in many supply chain contexts. Businesses must make inventory decisions in the face of uncertain demand, 
and the newsvendor problem provides a way to model this uncertainty and find optimal solutions.

## 3. An Example of Newsvendor Problem
Suppose a fashion retailer is introducing a new line of clothing and wants to optimize their inventory levels to maximize profits. 
The retailer has an existing inventory optimization system based on historical sales data that uses a benchmark model to forecast 
demand and estimate the optimal inventory levels.

The retailer's data science team decides to develop a more advanced deep reinforcement learning model that uses simulations to learn optimal inventory policies. 
The model is trained on a simulated environment that incorporates the dynamics of the retailer's inventory system, 
such as lead times, ordering costs, and backorder penalties.

The team evaluates the performance of the deep reinforcement learning model against the benchmark model and 
finds that the deep reinforcement learning model outperforms the benchmark model in terms of accuracy and prediction error.

The new machine learning model is deployed in the inventory optimization system, and the retailer starts to see significant 
improvements in their inventory management. The model is able to learn the optimal inventory policies for the new line of 
clothing based on the retailer's specific inventory system and the simulation environment, resulting in a reduction of 
stockouts and excess inventory. This leads to improved customer satisfaction and increased revenue and profits for the retailer.

Additionally, the deep reinforcement learning model can be updated over time as the retailer's inventory system and 
customer demand patterns change, further improving the retailer's ability to optimize their inventory and maximize profits.

To know more technical details about Newsvendor Problem with RL please check this [working paper](https://github.com/frankxujobs2023/frankxujobs2023.github.io/blob/master/assets/newsvendor_paper.pdf) of mine.
