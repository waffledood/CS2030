# SideProjects
My personal side projects!


# Project 1: Discrete Event Simulator

This was based off a school assignment where we had to set up a Discrete Event Simulator to simulate the environment of a shop 
where Servers serve incoming Customers.

Environment
- Servers are either Human Servers or Self-Checkout Counters.
- Human Servers are allowed to take breaks & this is determined by the probability of the Human Server resting.
- Human Servers have their respective queues of Customers.
- Self-Checkout Counters share a single queue of Customers.
- Customers are normal Customers or greedy Customers.
- Greedy Customers will choose to join the queue with fewest Customers.
- The arrival time of Customers to the shop, serving time of Servers & Human Server's rest times are achieved using a pseudo-random 
number generator (that is intialized with a seed, such that the same seed always produces the same sequence of seemingly random numbers).

Note: 
- This project was modified and uploaded for an event called Code With Friends (https://github.com/ScottKwang/CodeWithFriends-Spring2020)
