# Reinforcement-Learners-Games-and-Opinions
Reinforcement learners living on the vertices of a graph discuss an issue, and update their beliefs depending on the result of the conversation.

# Opinion-Propagation
In this model, neighboring nodes converse with one another, and randomly agree on opinion U or opinion V. If they agree on opinion U, each vertex increases its propensity to hold opinion U in the future (thereby affecting the probability distribution of future discussions). A similar update occurs if they agree on opinion V. This code models such interactions, and demonstrates the learners' tendency towards consensus. A paper proving the consensus of opinions for this model is in the works!

# Ultimatum game two players
In this model, two players play an 'Ultimatum Game'. This game involves player A offering player B a certain portion of a $100 dollar pool. Player B can accept (in which case player B gets their share, and player A gets the remainder), or reject (both players get nothing). This code studies the long-term behavior of the two reinforcement learners

# Coop game on graph
A generalization of the opinion-propagation code. Two connected nodes each play move U or move V, without knowing what the other node is playing. Players are rewarded if they play the same move. Note that this differs from opinion-propagation because 1) they are not forced to agree, 2) U and V might be associated to different reinforcement weights, 3) we explore different ways that a probability distribution for future moves is derived from the accumulated reinforcement weights 

# Prob of visitation Polya
The cooperation game above generalizes the classic Polya's Urn problem. I used this code in an attempt to simplify and understand the convergence properties of the players' strategies.
