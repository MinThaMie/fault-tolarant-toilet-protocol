# A fault-tolerant toilet seat protocol

## Abstract

In this article we propose a fault-tolerant protocol for toilet seat
positioning in a hostile environment.

## Assumptions

[Jay Pil Choi (2002)][1]`[1]` in his excellent article on toilet seat etiquette makes
the assumption that toilet users wish to optimize their toilet behaviour for
inconvenience cost. [Richard Harter (2005)][2]`[2]` also tries to find a cost optimum
and proposes three cost minimization candidate criteria:

> 1. Minimize the joint total cost
> 2. Equalize the respective total costs
> 3. Equalize the respective incremental costs

Although we shall not refute their findings given these assumptions, we
propose an altogether different metric to optimize for:

Given the fact that humans on average, regardless of gender, have very
little affection for toilet seats that are covered in feces or urine
<sup>[citation needed]</sup> we instead propose to optimize for toilet seat
cleanliness. This introduces a novel optimization challenge and a new
cost/benefit distribution across genders.

Secondly, both Choi and Harter assume that the parties in a toilet seat
sharing scheme are cooperative. Thus, they try to optimize for a situation
where both parties are receptive to a common solution. For our protocol
however will argue that the use of toilets should, in essence, be
considered a state machine in a hostile environment. This moves the
discussion into a different solution space, where fault tolerance and
protection against adverse agents become relevant.

### Optimizing for cleanliness

We make the assumption that a toilet seat in the `up` position is less likely
to be smeared than a toilet seat in the `down` position. Also, we refrain from
including the impact of air-borne bacteria due to leaving the toilet seat lid
open during flushing, for reasons or protocol simplicity. Research into both of
these areas is recommended.

### Optimizing for non-collaborative use

We propose the assumption that a generic toilet seat protocol should be equally
applicable in cooperative and hostile environments. We define hostile
environments as toilets in spaces where toilet users feel little or no shared
responsibility for the cleanliness of the toilet or the relationship with those
with whom the toilet is shared. In other words, the `conflict cost M` as defined
by Harter nears zero. We define cooperative environments as toilets in spaces
where toilet users do feel responsibility for keeping both the toilet clean and
the relationship intact. In other words, `M` nears one.

## Fault tolarant toilet seat protocol
Based upon the assumpations written above this protocol will optimize the experience of using a toilet in a non-collaborative setting.

1. Upon entering the bathroom you will find the seat in the `up` position.
2. When you want to sit down while defecating you move the seat to the `down` position.
3. After finishing step 2 you move the seat back in the `up` position.

## Social impact of the proposed toilet seat protocol
Eventhough it might be an unpopular stand point to have to put the toilet seat back into the upright posistion especially from a female perspective as shown by Choi, we argue that this protocol benefits everyone.
As shown by UK Bathrooms [4] the arguements around the toilet seat puts a strain on relationships. Hilt et al.[5] show that there are a lot of bacteria in urine which pose serious health hazards so reducing the chanche to catch these bacteria will benefit society. The largest problem with the proposed strategy is that it requires a change in behaviour. Changing behaviour is hard and requires time and effort. The most benefitial part of this protocol is that the toilet seat is always in the same state, upwards. Knowing this state and the required action will reduce the current frustration that arises from the suprise effect that women experience from sitting down on the toilet without a seat.

## Future research 
Gerba et al. [6] show in their research that there are merrits to closing the lid when flushing. Since this step does not influence the end state of the lid it is not part of the protocol eventhough it might be worth to address this topic when thinking about a toilet in a hostile, but even in a collaborative enviroment.

# References

1. [Up or down? A male econimist's manifesto on the toilet seat etiquette, Jay Pil Choi][1]
2. [A game theoretic approach to the toilet seat problem, Richard Harter][2]
3. [Relevant thread on Reddit][3]
4. [Biggest Cause of Petty Arguments for Co-Habiting Couples? Bathroom Etiquette][4]
5. [Urine Is Not Sterile: Use of Enhanced Urine Culture Techniques To Detect Resident Bacterial Flora in the Adult Female Bladder][5]
6. [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC187159/][6]

[1]: https://msu.edu/~choijay/etiquette.pdf
[2]: http://www.scq.ubc.ca/a-game-theoretic-approach-to-the-toilet-seat-problem/
[3]: https://www.reddit.com/r/dataisbeautiful/comments/2rzkcu/optimal_toiletas show_seat_strategies_oc/
[4]: https://blog.ukbathrooms.com/biggest-cause-petty-arguments-co-habiting-couples-bathroom-etiquette/
[5]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3957746/
[6]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC187159/
