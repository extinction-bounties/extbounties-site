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
illustrated previously.
[To keep the math simple](/side-topics/how-large-extinction-bounty/),
let's just say the fine is a flat $1 million per convicted person.

Anyone who exposes your secret stands to make millions by claiming a huge bounty
funded, in part, out of your own pocket. **You trust your team—but how much? How
sure are you *really* that everyone will stay quiet?**

This is where the true, game-theoretic "superpower" of FIBs
 step in, turning coworkers into
double agents.

## The economics of deterrence

In his field-defining work
[Crime and Punishment: An Economic Approach](https://www.nber.org/system/files/chapters/c3625/c3625.pdf),
Nobel Prize-winning economist Gary Becker showed
crime can be discouraged if the expected punishment outweighs the reward.
Expected punishment has not one, but *two* important factors:

- How *big* the punishment is, and
- How *likely* the punishment is to actually be levied.

Punishment likelihood itself depends on how likely the crime is to even be
detected in the first place, and then how strong of a case the prosecutors
can put together to how it really happened.

If you have ever wondered why older societies such as medieval Europe or
Qing dynasty-era China used the death penalty for so many seemingly minor
things, this is a big part of why. State authorities at that period of human
history had a very low chance of actually detecting something like e.g. forgery,
so in order to *deter* criminals they had to ratchet up just how big the
potential punishment actually was if you did get caught. Conversely, as our
societies have improved their ability to detect crimes, our stomach for policies
like "Forgery is punishable by death" has rightfully taken a nosedive.

The Fine-insured bounties approach takes this two-factor principle and 
runs a marathon with it. 
As we have alluded to, there is strong reason to believe that our odds of
crime detection and hence prosecurition rapidly climb to 100%, both because
specialized bounty hunters compete and innovate to get better at it, and because
there are simply *so many hungry eyeballs* just waiting for you to give them
a chance to cash you in. (Organized crime has some special considerations here
which FIBs are especially good at breaking through, in contrast to state-led
policing tactics.)

That near-perfect detection/prosecution rate gives us a lot of leeway in just
where we want to turn the dial in terms of how big the punishment is.
In Hanson's original formualtion, the fine for a crime should equal the
*full societal harm* of the crime, adjusted for the odds of getting caught.
We at Extinction Bounties suspect Hanson's "full societal harm" may in fact be
far in excess of what is needed to effectively deter true x-risks, but the
fines would be quite large on a per-person nonetheless.

Whichever way we choose,
when fines are set this high, and when quick detection is near-guranteed, 
the payout math changes dramatically. Suddenly, even
considering an illegal act like developing unsafe AI in public becomes 
extremely reckless. No rational
actor takes the risk if they're likely to lose far more than they'd gain. And,
generally, we expect people brilliant enough to become top AI researchers,
virologists, and the like to be pretty rational about their career choices.

## Organized crime and the game-theoretic superpower

Now, it's *theoretically* possible that one person, working in total isolation
from society, could develop a superhuman AI from scratch. But
this seems unlikely in a world so interconnected that 
[no one person can make a commercial pencil by themselves](https://www.youtube.com/watch?v=67tHtpac5ws).
In practice, one would need *capital* to purchase the eqiupment needed (GPUs,
etc.) as well as *labor* (coworkers) in many specializations to help run the 
project. Both of these create very reliable "heat signatures" of what someone 
might be trying to do.

If you agree with us that risking humanity for a science project, even slightly,
should be considered a criminal act, then such corporations should be considered
more akin to *organized crime* like mafia or drug cartels than e.g. Walmart or
Tencent.
Our standard policing regime does not deal with organized crime well; organized
criminals get very good at hiding their tracks and enforcing a code of silence
among their members. In a sense you could say they have
[specialized their labor in the production of crime](https://www.researchgate.net/publication/237517639_Conspiracy_among_the_many_The_mafia_in_legitimate_industries).

This is where game theory, the mathematical study of strategic
decisions, emerges to reveals a "superpower" inherent in FIBs. 
Normally, each person feels protected by the enterprise's code of silence 
among their peers. But with a big enough bounty, applied on a per-head basis,
**the person who defects *first* wins *big***. 
([Paying a bounty to yourself](/side-topics/what-about-turning-yourself-in/),
counterintuitive as it may seem, is a feature, not a bug here!)

It's an n-player version of the classic prisoner's dilemma: as the group grows,
the chance someone will defect and claim the bounty quickly rises to near
certainty. For example:

- With 10 conspirators, even if each person only has a 5% chance of betraying,
  there's a **40% chance** someone will defect.
  - Everyone has a 95% chance of *not* defecting. But the chances that
    *everyone* decides to not defect is then (0.95)^10, or about 60%.
- With 100 conspirators, that chance skyrockets to over **99%**.
- Even small increases in the bounty offered per offending individual can lead
  to huge increases in the average betrayal chance. $1000 for littering is
  tempting - $1 million *per person* for developing unsafe AI is borderline 
  impossible to resist when you have all of the org's secrets at your 
  fingertips.

In other words, **multi-agent conspiracies in particular are virtually doomed 
to fail** under a FIB regime, because even low individual betrayal probabilities 
compound dramatically. The loyalty must be *perfect* to avert this - nearly
impossible when early retirement awaits the first credible whistleblower.

Precedent for the exceptional corruption-busting power of bounties paid directly
to whistleblowers abound in the United States thanks to policies such as the
Security Exchange Commission (SEC)'s whistleblower awards and the False Claims
Act implemented in many states. While these are not fine-insured bounties
proper, they are similar enough to illustrate the efficacy of this part of
the mechanism. Here we illustrate two of the largest payouts in recent history.

### Exhibit A: Biogen’s marketing kick‑back plot funds a $266 million windfall

Former Biogen employee Michael Bawduniak spent seven years documenting covert
payments that steered doctors toward Biogen's multiple‑sclerosis drugs. When 
the United States Department of Justice settled the case for $900 million in 
2022, Bawduniak received **roughly $266 million**, or about 30% of the federal 
proceeds, under the False Claims Act (sources: 
[Department of Justice](https://www.justice.gov/archives/opa/pr/biogen-inc-agrees-pay-900-million-settle-allegations-related-improper-physician-payments), 
[PR Newswire](https://www.prnewswire.com/news-releases/largest-ever-266-4-million-whistleblower-award-in-biogen-false-claims-act-suit-301634323.html), 
[Bloomberg](https://www.bloomberg.com/news/articles/2022-09-26/biogen-to-pay-900-million-over-alleged-improper-doctor-payments)). 
Not bad for a few years of saved documents.

### Exhibit B: The $279 million Ericsson whistleblower

In May 2023 the SEC announced a record **$279 million whistleblower award**,
dwarfing the previous $114 million record set in 2020, to an insider whose tip 
helped uncover Ericsson’s multinational bribery network, a scandal the 
telecom giant had originally settled for about $1.06 billion in 2019
(sources: 
[Reuters](https://www.reuters.com/business/media-telecom/tipster-ericsson-won-secs-largest-ever-whistleblower-award-279-mln-wsj-2023-05-26/), 
[Department of Justice](https://www.justice.gov/archives/opa/pr/ericsson-agrees-pay-over-1-billion-resolve-fcpa-case), 
[SEC](https://www.sec.gov/newsroom/press-releases/2019-254)). 
The SEC has not
disclosed the whistleblower's identity in accordance with their whistleblower 
detection rules. 

The SEC program in particular has so far distributed 
[almost \$2 billion to nearly 400 insiders since 2011](https://www.sec.gov/enforcement-litigation/whistleblower-program) - proof to us 
that even the largest and best-hidden conspiracies reliably spring leaks when 
the first mover has such a strong incentive to do so.
Building on the SEC's phenomenal success, the United States Department of Justice 
launched a 
[Corporate Whistle‑blower Awards Pilot Program](https://www.justice.gov/criminal/criminal-division-corporate-whistleblower-awards-pilot-program)
that, in keeping with the game-theoretic defect-dominant strategy, rewards
only “the first to come forward.”

Astute readers will notice that the role of the liability insurer has not come
into prominence in this article. That is intentional - we will dive further into 
their unique role in this ecosystem later. We do think given the nature of the
crimes we are attempting to deter, they are a vital play, but for now we merely 
note that a well-designed mechanism generally has desirable outcomes even when 
[large parts of it are missing or not functioning as intended](https://how.complexsystems.fail/#2).

## Conclusion

The combination of economics and game theory makes Fine-Insured Bounties
uniquely powerful. They create intense, rational fear of committing wrongdoing
and foster distrust among potential co-conspirators. In practice, few crimes
remain secret, as betrayal becomes the dominant strategy.

Next, we'll examine how exactly this would apply to high-stakes fields like AI
research, transforming the culture of development from reckless competition to
careful compliance:
[The Goal - Making Frontier AI Devs Think Twice](/main-sequence/03-the-goal/).
