I’m David Luposchainsky, and this site is my public online ID card.

I’m probably better known as »quchen« in most online communities, or
occasionally as »blackout« in online games.

- **Email** dluposchainsky at the service of Google. PGP keys available on
  [Keybase][quchen@keybase]
- **Languages**
    - German (mother tongue)
    - English (you be the judge)
    - French (rusty, but enough to survive and read Wikipedia)
- **Nationality** German
- **Residence** Munich, Germany

Work-ish things:

- [Github][quchen@github]
- [Keybase (crypto keys)][quchen@keybase]

Social stuff:

- [Reddit][quchen@reddit]
- [Facebook][quchen@facebook]
- [Twitter][quchen@twitter]



# Work

## Current

I’m a senior software consultant at [TNG Technology Consulting GmbH][tng] in
Munich, Germany. Our core business model is sending groups of young, smart and
enthusiastic programmers on client projects that typically last for multiple
years, with individuals switching projects every 1-2 years.

To keep employees happy and passionate, we spend a huge amount of money on
education. I get to fly on conferences as much as I want, every other Friday
we’re allowed to pretty much do whatever we want as long as it’s at least
vaguely technology related, and our lenient »stuff ordering« guideline is a
staple of my bookshelf, ranging from quite readily applied to the highest of
ivory towers.

Overtime is compensated, I have 31.5 days off per year, I work around 41 hours a
week (contract demands 40), holidays carry over to the next year, and I can live
a comfortable life with my salary. And maybe best of all, I’ve never had to
touch a tie, or suit, or shirt.

## Education: Physics

I’m a physicist by education, which I studied at the University of
Würzburg/Germany (probably best known because Röntgen, the first Nobel
lauretate, is from), and at Rutgers/New Jersey/USA, where I spent a year abroad.

My Bachelor thesis was in experimental photoelectron spectroscopy (application:
thin film solar cells) because I wanted to work with big, impressive, and loud
machines before going into pen-and-paper theory. I followed that plan, and took
a detour to general relativity and high energy particle physics, before doing a
master thesis on non-equilibrium thermodynamics, where I studied spontaneous
decreases of entropy, and entropy production in nonequilibrium systems.

On my way, I developed an interest in pure mathematics, in particular in the
field of differential geometry at the time. The interest is still there, but the
domain has shifted a great amount to logic and type theory.

## No formal education: Programming and computer science

I have no formal education in dealing with computers, programming and what have
you. What I do have is a keen interest in it since around age 14, which led me
to a long path of self-education over the years. More about this can be found in
the »hobbies« section.



# Hobbies

## Programming

### Haskell

I’m an expert in [Haskell][haskell.org], a purely functional programming
language. I attained my knowledge from what I like to call IRC osmosis,
attending and [speaking][zurihac-stg] [at][haskellx-stg]
[conferences][haskellx-io], reading papers, writing lots of code for fun,
participating on the mailing lists, and organizing user groups.

My arguably biggest achievements in Haskell are [changing a core part of the
standard library][amp], and then [doing it again on a related, but different
topic][mfp]. This also established precedence for a now fairly popular and more
importantly safe way to make breaking changes within the Haskell community.

I’ve implemented [an interpreter for the lowest level intermediate
representation most commonly in use][stgi] for fun and learning. I think
compilers are the most interesting programs to write, because a lot of different
problems from different domains of computer science intersect in their creation.
I’ve found many of the attained skills immensely useful in other domains, and
even other programming languages.

### Programming languages

I have seen many different programming languages, used some of them, and a few
extensively.

I think **Haskell** is the best language for developing everyday
industrial-grade software, because I don’t have to think as much writing in it,
allowing me to focus on the task at hand instead of battling with the language
itself. Its support for refactoring even complex and poorly understood codebases
is unparalleled, and the type system not only helps me avoid loads bugs, but is
able to guide me towards a good solution as a sort of lab assistant. I think
Haskell has domains it’s poorly suited for by design and wish people would not
try to make it work in those areas.

I think **PHP**, which I have used extensively, is an intellectual insult, and I
have great disrespect for anyone evangelizing it.

I find the idea of failing fast and hard behind **Erlang/Elixir** very
interesting, and would like to learn more about it.

I think **Rust** is an upgrade to the mess that **C++** is (the latter I’ve also
used a lot), but unfortunately its type system is a huge price to pay.
Syntax-wise it’s pretty ugly, but I’ve gotten used to C++ at one point, so I’m
sure I’d be able to get used to Rust as well. It *does* combine many compelling
features, so I’ve given it a couple of (superficial) shots already.

I don’t really have an opinion about **Javascript**; given the original design
goals, it’s a remarkably good language. The idea behind Node.js’ asynchronicity
using callbacks from a single-threaded runtime is completely idiotic. The syntax
is average (i.e. bad), but I found Coffeescript to be a very much readable
dialect, although it hinders debugging a great amount.

**Mathematica** is an amazing tool for data science (and a terrible programming
language). It’s really a shame it’s closed source and proprietary, but it would
probably be unsustainable as a community-driven effort, considering the crazy
amount of time that goes into aggregating its vast and pretty coherent API and
data sources. I’m one of the people who bootstrapped
[mathematica.stackexchange.org][mathematica.stackexchange] during my studies,
back then (and to this day) the best help resource for the program.

### Computer science

I’m interested in type theory, and a very outspoken proponent of strong static
types. I’m familiar with advanced languages like Agda, and I’ve read many books
on the theory behind such languages. Their domains range from immediately
practical to what people in ivory towers would consier ivory towery.

I have a fairly broad, but not very deep knowledge of data structures and
algorithms. Most things I know by heart are from the functional domain, i.e.
persistent and typically amortized applications.

Although I’m interested in hardware and low-level programming, I could never
bring myself to do anything serious in that domain. I don’t know much about CPUs
beyond what one could build in Minecraft.

Sparked by advanced Haskell, I learned about category theory, and was utterly
disappointed by the return on investment. There that are equally challenging to
me, but much more fruitful both in terms of practice and follow-up ideas enabled
by it. The only thing understanding a monad from the math perspective taught me
is respect for those who recognized their practical relevance around 25 years
ago.

### Programming style

I take great pride in both pragmatism and elegance in my code. Pragmatism for me
is not »getting shit done«, which typically comes down to »getting *shit* done«,
but developing an well-understood and extensible solution to a particular
problem. Well-understood so that I am confident my solution is actually a
solution, and extensible so that instead of having to overengineer the code for
all possible scenarios, I can be confident that I can adapt to them reasonably
well, should the need arise. It does not mean cutting corners to save time,
using the debugger to insert special cases, or hoping the QA will find whatever
I forgot thinking about. Working in the latter mode on a regular basis causes me
great discomfort, and I believe it’s a very short-sighted and much more
expensive development process than doing it right from the beginning. If
business requires it, I am willing and capable to write atrocious hacks, but I
will insist in doing them right when time isn’t of the essence anymore.

I have never seen code that both was and was called »self-documenting«. I think
code should consist of excellent code with good documentation and tasteful use
of types.

Everything Robert C. Martin makes me angry. I’ll spare you the rant.



## Philosophy

I’m interested in philosophy the same way others are »interested in science«. I
like in epistemology due to its connection to physics and logic, and ethics and
morale due to its connection to everyday reality. I have not read many original
texts, but lots of secondary works, mostly online. I think [Existential
Comics][existentialcomics] is an amazing resource for appetizers to read up on.



## Sports

### Bouldering

I like bouldering because it’s a very social individual sport, which gives me
the best of all worlds: my achievements are solely based on my own abilities and
efforts, but they always happen within a group of people with a very supportive
and non-competitive mindset – people typically fight the rock together. Rock
gyms are excellent places to get to know a lot of people and make friends among
them; thanks to rock gyms, bouldering can be done with little time investment
and at any time of the day and year. Bouldering outside on the other hand
typically involves camping with little luxury and interesting and ambitious
people.

I’ve reached a plateau of Fb 7a/b difficulty, but I’m training a lot lately
hoping to get a 7c one day. My current projects are Splatch (7b) and Air Sweden
(7c) in Fontainbleau (at Élephant), and Grit Deluxe (7b) and Supernova (7c) in
Magic Wood. Rainbow Rocket (8a, Fontainbleau) is a dream, but might be out of
reach, but who knows!

### Gymnastics

I’ve started doing gymnastics again, which I haven’t done for six years. Some
skills are still there, most are gone. Still, I enjoy the trampoline, and am
having great fun exercising on rings, which are probably the most versatile
training tool in general, and certainly the one with the most bang for the buck.
Unfortunately, I’m very much terrible at them.

### Calisthenics

I recently started doing calisthenics, which is a form of urban body weight
exercise done on »a playground for adults« typically done outdoors on a rack
built for it, consisting of lots of metal rods to pull up and down on. The
people there are very friendly, helpful and non-competitive, but work very hard
on impressive skills such as the front lever or handstand variations. I’m making
good progress on learning the handstand, but front lever and muscle up will keep
me occupied for quite a bit longer – but it’s fun, and probably very beneficial
to my bouldering, where strength is my number one, pardon the pun, weakness.

### Mountain biking

My mountain bike hasn’t seen much use for a lack of time in the last years, but
I have fond memories of cycling two horizons a day in the Alps, far away from
civilization, and seeing landscapes inaccessible to hikers (because of the
boring distance to cover before reaching the nice spot) and cars.

### Not swimming

I don’t like swimming, but I do have a rule that when I’m at the sea or the
ocean I have to go in. I’ve stress-tested this rule on the Atlantic in March. I
regretted it, but not enough to abolish the rule.



## Other

Riding through the Alps on my **motorcycle** is amazing. It’s a peculiar mix of
calm and remote nature and the challenge to tame a stupid amount of power. I
don’t ever do anything seriously illegal with it though, since I can’t ride
anymore when I lose my license or life.

**Typography** is a domain of beautiful detail and rich history, but most people
don’t know about it, and fewer yet appreciate it. I like its subtlety, and that
it changes our way of thinking about the written words all around us, because it
brings an expressive, at times artistic component to otherwise fairly mundane
objects.

**Photography** is similarly becoming a niche activity, since phone cameras
commoditized taking pictures so much that it’s become difficult to justify
walking around aimlessly looking for a good picture, much like I would find it a
strange hobby if someone would just like to take the bus without really wanting
to reach a destination. For me it’s a very lonely hobby since I can’t stand
taking pictures when there are people around. I don’t think I’m very good at it
either, but I occasionally enjoy it nonetheless.



[amp]: https://wiki.haskell.org/Functor-Applicative-Monad_Proposal
[existentialcomics]: http://existentialcomics.com/
[haskell.org]: https://www.haskell.org/
[haskellx-io]: https://skillsmatter.com/conferences/8522-haskell-exchange-2017#program
[haskellx-stg]: https://skillsmatter.com/conferences/7276-haskell-exchange-2016#program
[mathematica.stackexchange]: https://mathematica.stackexchange.com/
[mfp]: https://prime.haskell.org/wiki/Libraries/Proposals/MonadFail
[quchen@facebook]: https://www.facebook.com/lupodavid
[quchen@github]: https://github.com/quchen/
[quchen@keybase]: https://keybase.io/quchen
[quchen@reddit]: https://www.reddit.com/user/quchen
[quchen@twitter]: https://twitter.com/quch3n
[stgi]: https://github.com/quchen/stgi/
[tng]: https://www.tngtech.com/
[zurihac-stg]: https://youtu.be/-MFk7PIKYsg
