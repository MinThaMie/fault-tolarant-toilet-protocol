# A fault-tolerant toilet seat protocol

## Abstract

In this article we propose a fault-tolerant protocol for toilet seat
positioning in a hostile environment.

## Assumptions

Jay Pil Choi (2002) in his excellent article on toilet seat etiquette makes
the assumption that toilet users wish to optimize their toilet behaviour for
inconvenience cost. Richard Harter (2005) also tries to find a cost optimum
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
