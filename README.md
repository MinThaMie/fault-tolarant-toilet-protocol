# A fault-tolerant toilet seat protocol


## Abstract

In this article we propose a fault-tolerant protocol for toilet seat
positioning in a hostile environment.


## Assumptions

[Jay Pil Choi (2002)][1]`[1]` in his excellent article on toilet seat etiquette
makes the assumption that toilet users wish to optimize their toilet behaviour
for inconvenience cost. [Richard Harter (2005)][2]`[2]` also tries to find a
cost optimum and proposes three cost minimization candidate criteria:

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


## Inter-agent comparison

Traditionally the literature considers the difference between male and female
toilet users. This makes sense since from a cost perspective, especially a
Harter `incremental cost` perspective, there is a significant difference between
male and female users.

This makes for a very bad starting point in our hostile, non-collaborative case.
We have two agents with diverging desires and differing costs, depending on the
chosen strategy. It makes sense that this leads to unresolvable conflict. We
take this as our starting point for this protocol, accepting that this inherent
difference in cost and desired outcome effectively makes each environment
hostile to some degree.

Optimizing for cleanliness changes this dynamic since both parties have a desire
for a clean toilet, but generally speaking with different tolerances for dirty
toilets, as we shall establish.

### Benefit analysis

The study of [C. Rose et al. (2015)][7]`[7]` shows an average defecation
frequency of 1.1 movements per 24 hours (with men having a slightly higher
frequency than women) and an average urination frequency of six movements per 24
hours. This, on average, makes for an approximate seven toilet visits per person
per 24 hours.

Of these seven visits, we expect female users to have an equally high preference
for a clean toilet on each visit. Of male users we would however expect that
they would display a high preference for a clean toilet one in seven times, with
a somewhat lower preference the other six visits.

It intuitively makes sense that each agent will have a stake in a clean toilet
relative to their respective requirements of said toilet. So we can expect to
see a higher willingness to advocate for and care for a clean toilet in female
users than in male users.

In both cases the benefit can be used as an incentive to apply a protocol that
is inherently self-serving (albeit not `selfish`, as per Choi's analysis).


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
6. [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC187159/][6]\
7. [The Characterization of Feces and Urine: A Review of the Literature to Inform Advanced Treatment Technology, C. Rose, A. Parker, B. Jefferson, and E. Cartmell][7]

[1]: https://msu.edu/~choijay/etiquette.pdf
[2]: http://www.scq.ubc.ca/a-game-theoretic-approach-to-the-toilet-seat-problem/
[3]: https://www.reddit.com/r/dataisbeautiful/comments/2rzkcu/optimal_toiletas%20show_seat_strategies_oc/
[4]: https://blog.ukbathrooms.com/biggest-cause-petty-arguments-co-habiting-couples-bathroom-etiquette/
[5]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3957746/
[6]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC187159/
[7]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4500995/
