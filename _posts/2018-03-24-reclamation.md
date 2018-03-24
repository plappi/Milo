---
layout: post
title: "Correct the incentives - clean-up the mines"
author: "Pauli Lappi"
categories: journal
tags: [documentation,sample]
image: open-pit.jpg
---
Mining is a messy business. To construct a mine large amounts material including topsoil and waste rock must be removed from the site.
Extracting, milling and refining the ore produces an end product, which may for example become something shiny on your finger or a frame for your new Tesla. 
But the operation produces
side-products including more waste rocks and tailings. What waits at the end of mine's life? A big hole with steep cliffs, waste rock piles and vast tailings
bonds with pollutants. These pose safety hazards and present possible adverse impacts on human health and to the environment. For example, waste rock piles may
cause acid mine drainage and pollute streams.

So what? Why is this problem? Waste rock piles can be covered or they can be used to fill in the holes. And tailings bonds are safely constructed anyway. 
In principle, yes, but in practice reclaiming the mine lands by the mining firm has not been that [simple or successful](https://www.sciencedirect.com/science/article/pii/S0301420709000531). It simply might not even occur - Just pay the 
small bond, and leave the more costly reclamation to the tax payers, as [has happened in the U.K.](https://www.theguardian.com/commentisfree/2015/apr/28/big-coal-keep-it-in-the-ground-energy-opencast-mines) 
Often, like [in Canada](http://vancouversun.com/business/local-business/underfunding-for-mine-cleanups-rises-to-more-than-1-27-billion), 
the monies deposited by the mining firms are not enough to cover the estimated reclamation costs. And, it's quite impossible not to mention here that Team Trump's recent 
[rollback on reclamation policy](https://www.theguardian.com/environment/2017/dec/17/donald-trump-epa-mining-pollution-rules)
 is not really happy news either.


It definitely looks like its possibly to readjust the instruments to give better results. The most important thing is to have a good estimate on the
future reclamation costs at the beginning of the mine's life. Of course, this estimate should be as close as possible to the real costs, which are revealed
in the future when the mine is shut-down and the reclamation is actually performed. Let's take an example from 
[Mitchell and Casman (2011)](https://pubs.acs.org/doi/abs/10.1021/es2021796),
 whose interest is on shale gas production.
Based on existing mining policies, they propose the following simple formula for the present value of reclamation costs $$P$$ to be deposited in a reclamation trust (or to be paid as a bond):

$$
P=\frac{C}{(1+r)^T}(1+V),
$$

where $$C$$ is the estimated reclamation cost, $$r$$ is the interest rate, $$V$$ is the volatility premium and $$T$$ is the life-time of the mine. Without commenting the 
volatility premium, this formula seems to produce the correct amount of funds to perform the reclamation assuming that the data is correct. However, there are at least two
problems with this formula and the line of thinking.

First, the formula does not pay any account to the benefits of the reclamation efforts. Presumably the only reason to spend
resources on reclamation is that it produces benefits to the people. Hence the benefits should be taken into account. A possible counter-argument is that the above cost $$C$$ has
already been compared to the benefits, and it has been found that benefits are greater than the cost; hence the decision to collect $$P$$ amount of funds. But by varying the 
reclamation effort, one varies the amount of benefits and costs. This means that a value that maximizes
 the net benefits should be found, and when found, one can use the above formula to calculate a different - possibly a more meaningful -  present value.
 
Second, and perhaps more importantly, Mitchell and Casman say that the reclamation cost $$C$$ is estimated in practice by the mining firm. This is a serious problem:

1. If the present value cost $$P$$ is not based on net benefit maximization, but simply on the mining firm's estimate, the cost will be understated. There's not going to be
sufficient funds for the eventual reclamation.

2. If the present value cost is based on net benefit maximization, it is in the mining firm's interest to overstate the cost, since it means lower required reclamation effort and cost.

Either way, and to say it plainly, shit hits the streams. However, even though the mining firm has better information about the future reclamation costs, the regulator is not totally
toothless; in principle the regulator can design a reclamation contract that the firm finds profitable to accept and which yields the maximal (expected) benefit for the society.

