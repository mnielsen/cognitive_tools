<!-- 1401 words -->
<!-- To do: Sutherland talk, and notes (+Ilya), spend 10-20 minutes on
games as cognitive tools, and on Bret Victor's work -->

_Very rough, incomplete (and often wrong) working notes on how to
create software tools that "enable people to understand and create in
unprecedentedly powerful ways" (Bret Victor).  I shall refer to such
tools as **cognitive tools**.  The purpose of the notes is to think
about the problem, to look at what other people have thought about the
problem, and to collect ideas for projects in the area._

**List of cognitive tools:** reading, writing, conversation,
  Mathematica, the multiplication algorithm, oblique strategies, the
  calendar, any method for monitoring oneself (e.g., lifelogging),
  money, attention managers, games, flashcards, libraries, programming
  languages, github, Google, table of contents, page numbers, cities.

**What can I contribute?  Where, if anywhere, is the comparative
  advantage to be found?**

**What principles can we use to build cognitive tools?**


# What can we learn from brain research?

**Look for bottlenecks in cognition:** What are our limits?  Can we
  get around them technologically?

**Are there ways we could overcome the well-known limits of working
  memory?** I wonder if there's a way of using visual cues to
  effectively outsource working memory.  In some ways we do this when
  we multiply two numbers on paper.  Might there be a slicker way we
  can do this more generally?
  
**Why not go and talk to some brain scientists to find out what the
  limits and the bottlenecks are?**

**Augmenting our senses:** Things like telescopes, microscopes, or
  infrared cameras are old examples of cognitive tools.

# Writing as a cognitive tool

**What is it about writing that makes writing powerful as a tool for
  thought?** We may ask the prior question: is writing a powerful tool
  for thought?  When we teach someone to write, does that make them
  smarter?  The obvious answer, I think, is that it only makes them
  smarter if they _practice the skill_.  Furthermore, writing _is_ a
  skill and it's possible to be better or worse at that skill. One way
  in which a writer can be skilled is that it makes them much smarter.
  
**How can one use writing to make one smarter?** One way is through
  purely formal means.  If someone asks me to square 123456 I can't
  easily do that in my head.  But it would be straightforward to do on
  paper.  

**What makes reading a powerful tool for thought?** The most obvious
  reason is that it allows us to acquire information that would
  otherwise be hard to come by.  There is, in principle, little that
  can't be done in conversation that can be done through print.  But
  in practice we have limited conversational resources.  Writing
  scales better than does access to conversation.  The flipside to
  this is that conversation is in some ways a richer medium than
  writing, and as a result there are things we can learn easily in
  conversation

**Reading can make us more creative:** This is a way in which reading
  can make us smarter which is not about the acquisition of
  information.  And that's by stimulating.  Indeed, it's possible to
  be good at one type of reading (say, creating new ideas), and not so
  good at another (say, acquiring information).

**Is reading a more powerful tool for thought than writing?** 

**Cognitive tools make us think different, not necessarily smarter:**
  Every research scientist knows someone who spends too much time
  reading the past literature.  It's a classic failure mode: the
  researcher whose first response to hearing of problem is to go and
  start looking up what's already been done, rather than beginning to
  think about the problem themself, and develp their own independent
  point of view.  Of course, ultimately it's often helpful to do both,
  but it's rarely a good idea to leap straight into intensive reading.

# Indices

One interesting cognitive technology is the index.

**What makes indices a powerful tool for thought?** They expand the
  range of information we can find.  When I read a book I no longer
  need to memorize the details of the contents.  Instead, I can
  memorize things at a coarser grain, knowing that I can go and look
  up details when I need.  Basically, an index expands our access to
  knowledge.  It effectively gives us a bigger database of facts to
  draw on.

**The pattern: Cognitive technologies break bottlenecks in our
  brain:**

# Ideas about how to make people smarter and more effective

**What are the best ideas we have about how to make people smarter and
  more effective?** I think there are two such ideas:

1. Desire: People need to be responsible for, and reap the benefits
of, their own learning.  If they are, they will take ferocious control
over their own learning.  A huge mistake made by the education system
is to ignore this fact: most 14 year-olds in the classroom have no
desperate personal need to learn, and there is only a little that even
the best-intentioned teachers can do to change that.  Indeed, it is a
natural consequence of being in the classroom: the work done there
matters only a little, and smart 14 year olds know it, and respond
with an appropriate attitude.  Unfortunately, someone without a strong
desire to learn is probably not a very effective learner.  Once
someone develops a very strong desire to become more effective, then
they begin to seek and benefit from learning opportunities at a
tremendous rate.

2. Environment trumps everything except desire.  Perhaps 100,000
people lived in Florence in the mid 1400s.  People born there (or in
the countryside just outside) included Michaelangelo, Botticelli, and
Donatello, as well as many other famous (but not quite as immortal)
artists.  Now, you start to do back-of-the-envelope calculations, and
someone born in Florence at that time was perhaps 10,000 times more
likely to be an immortal artist than an aspiring artist today.  In
other words, the best way to become a great artist wasn't to be born
very talented, or be inspired by some special muse or whatever.  It
was to live in Florence in the late 1400s.  That choice of environment
completely swamped "natural talent" and just about every other
variable I can think of, _except_ desire.

I'd say these conditions are very close to necessary and sufficient
conditions.  Conditions 2 is not quite necessary --- one can think of
examples where it has not been met.  But as the Florentine example
shows, it is tremendously important, probably far more important than
we think.

**Much of what we believe about learning is false:** This is a
  corollary to the above remarks.  It follows from the observation
  that schools get something very basic wrong: they don't understand
  the primary nature of desire for learning, and how difficult it is
  to develop that desire when you treat children in the paternalistic
  manner that underlies schooling.  This is an example of a false
  belief, in this case one that's predicated on a (very widespread)
  **false model** of how we learn.  Another good example of how we use
  false models comes from Tim Gallwey's work on the inner game,
  showing how conventional models of coaching fail, since they
  actually create internal interference.  A consequence of all this is
  that I should feel free to **re-examine the basics**, and to
  **identify (and then challenge) conventional wisdom**.

# Dealing with abstraction

**How to deal with abstraction?** _finding multiple representations_,
_simplifying_, _approximating_, _finding the salient feature_.  All
these may be used in combination.  One way of building software tools
to help us think is to build software tools that make it easier to do
these things.

_Multiple representations:_ It helps us dramatically when we can find
ways of representing a new abstraction in terms of something else that
we already have ways of working with.  Think of the way we can
understand Hermitian matrices in terms of their eigenvalue
decomposition, for example.

_Simplifying the abstraction_: Consider the way we can simplify a
topological space down to a number, by counting the number of
connected components.  This provides information that can, for
example, be used to prove that two topological spaces are not
homeomorphic.

_Approximating the abstraction:_ A cow is not perfectly spherical, but
to a good approximation... To work, we need to develop a good
understanding of how to control the impact of the approximation.

_Finding the salient feature:_ This is often the key to solving
problems.  

# Games

**Are games the only way?** Marshall McLuhan once commented that
"Anyone who tries to make a distinction between education and
entertainment doesn't know the first thing about either."

**What makes games such a great tool for thought?**
  [Watch this guy play Tetris](http://www.youtube.com/watch?feature=player_detailpage&v=jwC544Z37qo#t=171s).
  I won't spoil the surprise, but the last minute or so is almost
  beyond belief.

**People get amazingly good at games, very, very quickly.  Why is
  this?  Why do they get good so much faster than they do with other
  kinds of learning?**

**A related question: why do people remember so much more from movie
  trailers than they do from 2-3 minutes of other material?**

**Why do we easily tolerate repetition of some material but not of
  others?**

**How much does it help to add sound?** I'll bet it helps a lot.

# Source material

**Who is working on this?** Many people and organizations are working
  on this problem.  Looked at a certain way, for example, it's a
  problem that many software companies are working on.  But often they
  don't _think_ they're working on this.  They may be primarily
  focused on trying to turn a profit.  Or if they do think they're
  working on this, it's a secondary motivation.  Motivation matters.

**Bret Victor:** One of the people who is most consciously working on
  this problem is [Bret Victor]().

**Bret Victor's principle:** Very roughly speaking, it's to make the
  output of code fully visible, in real time.  What makes this such a
  powerful principle is that it means that we can take something
  abstract (a program), and then give it another representation (the
  visualisation), and then flip back and forth between the two.

**Is there a good way of building Victor's visual representation
  easily into the program?**

**Get Victor's principle more correct:**

**Explore the links on Victor's page as stimulus:**

# Project ideas

**Attention manager:**

**Essay on how online tools can amplify our collective intelligence:**

# Other material

**Task management:** One of the hardest things we can do.

**What would it mean to make mathematics executable?**

**"The interface fundamentally determines behaviour":**
  ([Rory Sutherland](http://www.ted.com/talks/rory_sutherland_life_lessons_from_an_ad_man.html)
  This is an improved version of "the medium is the message".

**What can we learn from?**

**Who is working on this?  Which aspects are there too many people
working on?  Which aspects are there too few people working on?  What
are some ideas I can bring in from left field?** MIT Media Lab.
