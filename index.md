# A State Representation for Diminishing Rewards

Here we present GIFs of agents trained using the &lambda;R across several navigation domains. A consistent theme is that accurate policy evaluation using the ``correct'' &lambda; leads to stronger performance. Using a &lambda; which is too high typically leads to overstaying at reward locations, while a &lambda; which is too low leads the agent to abandon rewarded locations too early. 

## Policy Learning in TwoRooms

In this this setting the true &lambda; is 0.5.

Agent &lambda; = 0.5:

![Q-lambda learning](q0.5.gif)

Agent &lambda; = 0.0:

![Q-lambda learning](q0.0.gif)

Agent &lambda; = 1.0:

![Q-lambda learning](q1.0.gif)

## Policy Composition in FourRooms



## Replenishing Rewards in TwoRooms

![Q-lambda learning with replenishing rewards](0.5_replenish.gif)


