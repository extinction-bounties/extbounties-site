---
title: '02. The Gist - Using Economics and Game Theory to Stop Criminals Before They Start' 
weight: 2 
draft: false
---

## A word before we start on our focus

If you’re sold on the basic mechanism after the candy-wrapper example, great! 
We're glad it was an accessible illustration of how private incentives, paired
with smart legislation, can quickly and cheaply reshape behavior at scale.

As you can probably guess by our title, our *real* focus at Extinction Bounties 
is applying this same fine-insured bounty (FIB) model, with some small
modifications, to something much more serious: **Existential risks arising from 
novel technological research** - the so-called "black balls" of 
philosopher Nick Bostrom’s 
[Vulnerable World Hypothesis](https://nickbostrom.com/papers/vulnerable.pdf), like misaligned AI, engineered pandemics, and "grey goo" nanotechnology. 

We’re *not* here to convince you that these dangers exist. Other people have
already done that far better than we could:

- For a thorough overview of existential risks (x-risks) in general, 80,000 Hours’ 
  [The case for reducing existential risks](https://80000hours.org/articles/existential-risks/)
  is our favorite starting point. 
- For a thorough introduction to the x-risk posed by the development of
  artificial intelligence (AI), [AISafety.Info](https://aisafety.info/) is our
  go-to primer on the topic.  

Our goal here is merely to discuss *how* to deter these kinds of risks using the
mechanism we propose, and *why* we think it has some unique properties that make
it a powerful deterrent for a class of risks that has so far proven very
challenging to deal with at scale.

(One last thing:
Unsafe AI is our "default" x-risk for discussion on this site, not
because it is very differnt in kind from e.g. gain-of-function research from the 
point of view of our mechanism, but 
because experts we respect agree it poses the greatest
threat of any novel technological development in the near future. 
If you disagree with us on that feel free to mentally replace "unsafe AI" with 
[the Torment Nexus](https://knowyourmeme.com/memes/torment-nexus) while reading.
Okay, onward!)

---

*Previous: [01. The Hook - What if Wrongdoers Paid for Their Own Busts?](/main-sequence/01-the-hook/)*

Imagine you're part of a group developing an illegal, ultra-powerful AI. Imagine
further that anyone getting caught assisting in the development of more powerful
frontier AI models is punishable by a fine-insured bounty (FIB), like we
illustrated in
[The Hook - What if Wrongdoers Paid for Their Own Busts?](/main-sequence/01-the-hook/).
Anyone who exposes your secret stands to make millions by claiming a huge bounty
funded, in part, out of your own pocket. You trust your team—but how much? How
sure are you that everyone will stay quiet?

This is where economics and game theory step in, turning co-conspirators into
competitors.

## The economics of deterrence

The idea traces back to Nobel Prize-winning economist Gary Becker, who showed
crime can be discouraged if the expected punishment outweighs the reward.
Fine-Insured Bounties (FIBs) take this principle and run a marathon with it: in
Robin Hanson's original formulation, the fine for a crime should equal the *full
societal harm of that crime*, adjusted for the odds of getting caught. (We at
Extinction Bounties suspect this is in fact a far overestimate of what would be
effective to break up virtually all criminal enterprises of interest to us —
that's a good thing!)

When fines are set this high, the math changes dramatically. Suddenly, even
considering an illegal act becomes extremely financially reckless. No rational
actor takes the risk if they're likely to lose far more than they'd gain. And,
generally, we expect people brilliant enough to become top AI researchers,
virologists, and the like to be pretty rational.

## The game-theoretic trap

But it's not just economics. Game theory—the mathematical study of strategic
decisions—reveals another layer of power in FIBs. Consider the scenario again:
multiple people secretly developing banned technology. Normally, each person
feels protected by the "blue wall of silence" of their coworkers. But with a big
bounty, the person who defects *first* wins *big*.

It's an n-player version of the classic prisoner's dilemma: as the group grows,
the chance someone will defect and claim the bounty quickly rises to near
certainty.

For example:

- With 10 conspirators, even if each person only has a 5% chance of betraying,
  there's a **40% chance** someone will defect.
  - Everyone has a 95% chance of *not* defecting. But the chances that
    *everyone* decides to not defect is then (0.95)^10, or about 60%.
- With 100 conspirators, that chance skyrockets to over **99%**.
- Even small increases in the bounty offered per offending individual can lead
  to huge increases in the average betrayal chance.

In other words, **multi-agent conspiracies are virtually doomed to fail** under
a FIB regime, because even low individual betrayal probabilities compound
dramatically. The loyalty must be *perfect* to avert this—which is nearly
impossible when millions of dollars await the first credible whistleblower.

**The Result:**\
The combination of economics and game theory makes Fine-Insured Bounties
uniquely powerful. They create intense, rational fear of committing wrongdoing
and foster distrust among potential co-conspirators. In practice, few crimes
remain secret, as betrayal becomes the dominant strategy.

Next, we'll examine how exactly this would apply to high-stakes fields like AI
research, transforming the culture of development from reckless competition to
careful compliance:
[The Goal - Making Frontier AI Devs Think Twice](/main-sequence/03-the-goal/).
