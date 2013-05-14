# Working notes on cognitive tools

Rough and incomplete working notes on how to create tools that "enable
people to understand and create in unprecedentedly powerful ways"
(Bret Victor).  I shall refer to such tools as _cognitive tools_.  The
purpose of the notes is to think about the problem, to understand some
of what other people have thought about the problem, and to collect
project ideas.

**What would it take to get the average person to understand general
relativity?** Could we develop general cognitive tools to make it that
easy?  (C.f. Augustine as the "smartest person in the world" due to
being able to read without speaking.)  It may be that _motivational
hacks_ are the key.


**What can I contribute?  Where, if anywhere, is my comparative
  advantage to be found?**



**The comparison to self-help:** Self-help gets a bad rap.  Many of
these software tools have a similar goal, though, which is to improve
the way we think.  Yet a concrete tool like (say) org mode seems to
have significantly more impact than lots of what you see in the
self-help books.  It's a type of executable or active self-help.  That
shift from passive self-help, which is often vague and unactionable,
to active self-help (which is by its nature very concrete) makes a big
difference.

# Observations

**What principles can we use to build cognitive tools?**

**Cognitive tools often make easy cognitive tasks that were formerly
hard:** It requires careful thought to understand why (and when)
automating a formerly difficult task can make us smarter.  Sometimes,
solving a big problem, X, has a bottleneck, Y.  Absent a way of
avoiding the bottleneck entirely, we need to find a way of solving Y.

**Principle: We could all do with having more cues in our life:** I
  wonder about having a unique buzzer for each habit I'd like cued?

# What's going on when we multiply two numbers on paper?

Most of us find it challenging to multiply two-digit numbers in our
heads.  And yet, with a paper and a pencil, it becomes almost trivial
to do.

This seems unsurprising, because it's so familiar.  But it's really
quite a remarkable phenomenon: someone hands you some tree pulp and a
piece of graphite embedded in some wood.  And this lets you trivially
do tasks that were impossible before.  What, exactly, is going on?

At some level, it seems almost obvious: multiplying two numbers in our
head taxes our short-term memory.  We lose track of intermediate
results, and so have to start the calculation over again.  The use of
pencil and paper gives us a way to overcome the limitations of our
short-term memory.

That's a nice explanation.  But it's pretty vague.  Let's see if we
can better understand what's going on by working through a detailed
example.  Suppose we're trying to multiply 123 by 456.  I'll work
through the operations involved.  Of course, there's nothing new here
(!)  --- I'm going through this simply to give us a concrete reference
point to start thinking about what, exactly, is going on.  Here's the
example:

>   123
> x 456

Using the grade school multiplication algorithm, I start by
multiplying the rightmost digits of both numbers, i.e., 6 by 3.  This
gives me 18, so I write down 8, and "carry the 1":

>   123
> x 456
>   ---
>     8 carry 1

Incidentally, the way I was taught the multiplication algorithm in
school, it was usual to write the carried digit as a superscript to
the left of the 8.  I haven't done that here, because it's
inconvenient.  I'll come back to this point a bit later.

The next step of the procedure is to multiply the rightmost digit of
the bottom number (6) by the second-to-right digit of the top number
(2).  That gives us 12, to which I add the carried result (1), to get
a total of 13.  So I write down 3, and again carry the 1:

>   123
> x 456
>   ---
>    38 carry 1

Then I multiply 6 by 1, and add the carried digit, to get 7, with
nothing carried.

>   123
> x 456
>   ---
>   738

Next I do essentially the same procedure, but for the 5 in 456.  It's
very similar, with lots of single-digit multiplication, carries, and
additions.  The final result is:

>   123
> x 456
>   ---
>   738
>  615

And then finally I do it for the 4 in 456:

>   123
> x 456
>   ---
>   738
>  615
> 492

Then we add the three rows below the "---". I won't explicitly write
out all the operations involved --- they're along much the same lines
as before.  But we get a final result:

>   123
> x 456
>   ---
>   738
>  615
> 492
> ---
> 56088

What operations were involved? The most complicated arithmetic
operations involved were just the multiplication or addition of two
single-digit numbers.  About the most complicated thing we did was the
very first step: multiplying 6 by 3 to get 18.

**Variations:** An interesting thing about the procedure is that there
are some ambiguities in how operations are carried out.  For exampe,
in the second step of the procedure I multiplied 6 by 2 to get 12, and
then added the carry (1), to get a total of 13.  But I could equally
well have started with the carry (1), and then added 6 by 2 (12), to
get 13.  A disadvantage of doing that is that it requires me to keep
more information in working memory.  Not a lot more, but enough to be
a little taxing.  An advantage is that I wouldn't have needed to write
down the carry digit, since in this approach the only time I use the
carry digit is immediately after learning its value.

**Why is it easier to remember where things are stored than to
remember what is stored?** The same information is involved.  But I
don't need to store it in working memory.  It's on the paper.  But
there's a problem: how do I find it?  Naively, it seems as though I'd
have to remember the paper locations where the information is stored.
Why isn't recalling those locations just as hard as remembering the
information to be stored?  In fact, when people are just learning to
multiply for the first time, this really is a problem, and they get
confused about where to look for the information they need.  But
experienced multipliers have committed an algorithm to long-term
memory.  That algorithm tells them how to organize the information on
paper so that they can find the information they need, when they need
it.  In other words, *by committing an algorithm for organizing and
finding information to long-term memory, we can outperform short-term
memory alone*.

**Reading, learning, and emotion:** Some of the power of reading is
  that it lets us learn from others, when we otherwise couldn't.  We
  have a major cultural deficit, though, which is that conventionally
  we strip much of the emotional content.  Scientific prose tends to
  be dry, not because it must, but because it is forced to be so by
  convention.  It thus loses much of its power to teach.

# What can we learn from brain research?

**Look for bottlenecks in cognition:** What are our limits?  Can we
  get around them technologically?

**Are there ways we could overcome the well-known limits of working
  memory?** I wonder if there's a way of using visual cues to
  effectively outsource working memory?  We already do this, for
  example, when we multiply two numbers on paper.  Might there be a
  slick way we can do this more generally?  Whiteboards are a way of
  doing this.
  
**Why not ask some brain scientists what the limits and bottlenecks of
  our minds are?** My sense is that one thing we could do with a lot
  more of in our lives is the right cues.

**Augmenting our senses:** Things like telescopes, microscopes, or
  infrared cameras are old examples of cognitive tools.

**I don't understand what makes something memorable:** Why, when I
  watch a good movie trailer or listen to a great piece of music, do I
  remember it? What makes an explanation memorable?  What makes
  something *vivid*?
  
**The poverty of the verbal:** Many intellectuals love verbal content,
but don't really quite get other types of content: movies, music
videos (say), and so on.  (Exceptions are made for "respectable"
artforms, such as classical music, which have a strong intellectual
verbal tradition associated to them.) I've talked to people whose only
opinion about the movie _Avatar_ was that the plot and dialogue
weren't very good.  That was to miss the point.  If verbal content is
everything then that's a reasonable point of view.  But _Avatar_ has
astounding non-verbal content, and those people largely missed that
content, or else got hung up on details.
    
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

# List of cognitive tools

**Cognitive tools to think about:** reading, writing, conversation,
  any algorithm, Mathematica, oblique strategies, the calendar, any
  method for monitoring oneself (e.g., lifelogging), money, attention
  managers, games, flashcards, libraries, programming languages,
  github, Google, table of contents, page numbers, cities.

**Prompting or checklisting:** A simple, powerful pattern is to be led
  through a series of prompts or checklists.  See, e.g., Gatawande's
  book on checklists for a good case that this can really improve
  performance.
  
**Choice architecture:** See, e.g., Sunstei and Thaler's book _Nudge_
for discussion of how the way choices are presented to us can
influence our cognitive capability.

**Indices:** What makes indices a powerful tool for thought? They
expand the range of information we can find.  When I read a book I no
longer need to memorize the details of the contents.  Instead, I can
memorize things at a coarser grain, knowing that I can go and look up
details when I need.  Basically, an index expands our access to
knowledge.  It effectively gives us a bigger database of facts to draw
on.

**What criteria should we judge a cognitive tool on?** That it expands
  the range of cognitive tasks that we can reasonably perform.

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

**What can we learn from games?**

**Why are so many educational games terrible?** I think the problem is
  that many of the theories from the educational literature aren't
  very good.


**What makes games such a great tool for thought?**
  [Watch this guy play Tetris](http://www.youtube.com/watch?feature=player_detailpage&v=jwC544Z37qo#t=171s).
  I won't spoil the surprise, but the last minute or so is almost
  beyond belief.

**Are games the only way?** Marshall McLuhan once commented that
"Anyone who tries to make a distinction between education and
entertainment doesn't know the first thing about either."


**People get amazingly good at games, very, very quickly.  Why is
  this?  Why do they get good so much faster than they do with other
  kinds of learning?**

**A related question: why do people remember so much more from movie
  trailers than they do from 2-3 minutes of other material?**

**Why do we easily tolerate repetition of some material but not of
  others?**

**How much does it help to add sound?** I'll bet it helps a lot.

# Active reading and explorable explanations

This is an idea of Bret Victor's.  The idea is to make documents
interactive so that the read can easily modify elements of the
document and, in real time, other elements will change in response.
It's a way of exploring what's going on.

**Reactive documents:** A synthesis of spreadsheet and document.
  Elements of the document can be modified, which in turn updates
  other parts of the document.  Victor has a Javascript library,
  [tangle](https://github.com/worrydream/Tangle), which can be used to
  author reactive documents.  I could potentially write a reactive
  document for my blog.  Here's a
  [WordPress page](http://codex.wordpress.org/Using_Javascript) about
  how to include Javascript in just a single post.
  
**The advantage over spreadsheets:** Victor makes the point that while
  spreadsheets are great, they don't explain the model that they
  implement.  Reactive documents could _explain_ the model and
  simultaneously allow people to _explore_ the model.  Here's Victor:
  
> "a spreadsheet is not an explanation.  It is merely a dataset and
> model; it cannot be read.  An explanation requires an author, to
> interpret the results of the model, and present them to the reader
> via language and graphics.

**Explorable explanations enable discovery:** You can play with the
  parameters, and by looking at the consequences you start to have
  suspicions about what is true, and may even be able to empirically
  establish some of your suspicions.
  
**Explorable explanations stimulate questions**

**Interactivity is not the point; combining exploration and
  explanation is the point:** Here's Victor on this:

> It's tempting to be impressed by the novelty of an interactive
> widget such as this, but the interactivity itself is not really the
> point. The primary point of this example -- the reason I call it an
> "explorable explanation" -- is the subtlety with which the
> explorable is integrated with the explanation.  
>
> Like the proposition example earlier, the filter description works
> as a static explanation -- it can be read like normal text. The
> reader is not forced to interact in order to learn. The reader
> interacts if he wants to go deeper, if he has piqued curiosity or
> unanswered questions. There are no UI elements screaming for
> attention. The reader is not transported off to a separate
> "interactive" context. Instead, the reader simply nudges the
> examples that the author has already presented.
>
> Most interactive widgets dump the user in a sandbox and say "figure
> it out for yourself". Those are not explanations. To me, an
> essential aspect of the "explorable explanation" concept is that the
> author holds up his end of the conversation. The author must guide
> the reader, and provide a structure for the learning
> experience. Only then can the reader respond, by asking and
> answering the questions that the author provokes.

I guess people often draw a distinction between a model we can play
with (like, for example, a spreadsheet), and an explanation.  Victor's
key idea here is to _integrate_ the two, and that we gain something by
doing that integration.  

**What happens when we step outside the model?** This is 

**Use cases:** With something like this I think it's a mistake to ask
  the question "So what could it be used for?"  Instead, it'd be
  better to simply try out lots of use cases, and see what works well,
  and what doesn't.
  
**Building a simplifed version of tangle:** I took a look at the
  library.  It's very nice.  However, the API is pretty complicated.
  It'd be nice to have a templating system that made it a lot easier
  to use tangle.  Maybe a Wordpress plugin that made it trivially
  possible to compile to tangle?

**What's a neat reactive document that I could write?** Maybe one that
  showed off the ideas of relativity?  Maybe one that did some kind of
  scenario planning along the lines championed by the futurists?
  Maybe I could include it in my Clock of the Long Now essay, for the
  analysis of the relativistic clock?  

**Explorable examples:** Victor gives a very beautiful example of a
  digital filter where you can literally move the parameters of the
  filter around, and dynamically see how the frequency response
  changes.
 
**Could we combine tangle with mathjax?** That'd be a fun project!

**Text as an environment to think in:** Here's Victor:

> The goal of Explorable Explanations is to change people's
> relationship with text. People currently think of text as
> information to be consumed. I want text to be an environment to
> think in.

**Scientific communication as sequential art:** Another of
[Bret Victor's ideas](http://worrydream.com/#!/ScientificCommunicationAsSequentialArt).
I was struck by the following, which seems to sum up much of Victor's
philosophy:

> When an algorithm is described in prose (or code), we are typically
> given only the rules of the system — we can't see the data or the
> state. In order to understand what the algorithm is doing, we have
> to "play computer" and imagine the state in our head. Illustrating
> the state of an algorithm at each step can make the description
> dramatically easier to follow.

Furthermore, Victor does this in such a way that's not merely an
illustration, but there is actually

**Core idea: using multiple representations of concepts, and coupling
  those representations, so we can interact with them in different
  ways:** We could imagine doing this to illustrate something like the
  eigenvalues of a Hermitian matrix.  We could have two coupled
  descriptions:
  
  matrix <=> eigenvalues and eigenvectors
  
  We could interact with either description, and see how it affects
  the other.
  
**Scientific communication and comics:** More from Victor:

> Finally, "comic-style" needn't mean characters, dialog, word
> balloons, or sound effects. Let alone superheroes or anthropomorphic
> animals. The comic form is about sequences of tightly-integrated
> words and pictures, together conveying a message more powerfully
> than the sum of their parts. The potential of this form to explain
> difficult concepts is unmatched and underused.

I am strikingly reminded of Manny Knill's idea of writing a paper that
would just be figures to illustrate the Solovay-Kitaev theorem.
Essentially Manny was proposing exactly what Victor is suggesting
above.

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

# The current status of work on cognitive tools

Much of the best work in the early days of computing was aimed at
developing cognitive tools.  Pioneers such as Douglas Engelbart, Alan
Kay, and Ted Nelson all struggled, in different ways, with the
question: "How can we build better cognitive tools?"  For reasons I
don't entirely understand, today few people are squarely addressing
this question.  There _is_ good, practical work coming from the many
companies and organizations which are creating products that change
how we think.  But that work is oriented toward the development of
monetizable products, not directly about developing a deep general
understanding of cognitive tools.  The academic work on the subject
seems, with some notable exceptions, dull and uninspired.

I find this strange.  Many of humanity's greatest inventions are
cognitive tools --- language, the alphabet, mathematics.  These tools
enable our minds to pull themselves up by their mental bootstraps.
Tools such as word processors and visualization software push this
tradition further.  It's easy to be snide and remark that _Microsoft
Word_ doesn't seem like _quite_ as much of a jump as the invention of
the alphabet.  But the invention of the alphabet didn't happen all at
once.  It took thousands of years to develop all the ideas used in
modern alphabets.  We've had word processors for just a few decades.

# Project ideas

**Attention manager:**

**Essay on how online tools can amplify our collective intelligence:**

# Programming languages

**Programming languages are tools for thought**

**Smalltalk arose from a vision of a programming language as a
  learning environment**
  
**[Alan Kay on Smalltalk's design](http://www.smalltalk.org/smalltalk/TheEarlyHistoryOfSmalltalk_Introduction.html):**

> Smalltalk's design--and existence--is due to the insight that
> everything we can describe can be represented by the recursive
> composition of a single kind of behavioral building block that hides
> its combination of state and process inside itself and can be dealt
> with only through the exchange of messages.

In other words, objects can be decomposed into smaller objects, and so
on, _ad infinitum_.  This is taking a metaphor from physics, and
turning it into a way of describing active knowledge.

**What would force-based programming look like?** Could we use
  potentials?  What about Einstein's idea in GR?  Prolog already uses
  something like a Lagrangian point of view.
  
**How important are programming languages as cognitive tools?** This
  seems like a key question.  What is maybe interesting about
  programming languages (and, to some extent, media more generally) is
  that they can be used to create new types of cognitive tool.  In
  some sense they're a meta-cognitive tool.  And so as you master
  programming you can start to build more and more powerful cognitive
  tools for yourself, and for others. 
  
  
# All Our Knowledge

## Writing

**Writing principle:** It should make ideas vivid.  It should be
  coherent. 

## Community and collaboration

**It's more important to be polite than to be right:**


# Other material

**Task management:** One of the hardest things we can do.

**What should I do next?**

**When do cognitive tools help?  When do they hinder?  When does
  access to the net make us smarter?  When does it make us stupider?
  What other effects does it have?**

**What is a cognitive tool?**

**Something that does for habit what Google does for factual memory**

**The intangibility of cognitive tools:** I'm having a strange feeling
  as I grapple with these notions of cognitive tools.  It's that I
  can't fully grasp what these tools actually do for us.  They have an
  intangible quality.  Think about how strange it is to not have the
  notion of zero, or of negative numbers.  It's easy to overlook these
  notions.
  
**Institutions are some of our best cognitive tools:** SOmetimes
  unintentionally, too.  People think "Oh, Steve Jobs must be so
  smart."  But much of his smartness was a _consequence_ of being in
  charge of Apple, not the other way round, which is how people tend
  to think.
  
**Why are all these projects of Victor's just at the prototype
  stage?** I think the answer is that there's really two very hard
  tasks here.  One is developing interesting prototypes (which Victor
  has done, as PARC did, and so on).  The other is developing those
  prototypes into mass market products.  Both tasks are tremendously
  difficult to do.
  
**What would it mean to make mathematics executable?**

**"The interface fundamentally determines behaviour":**
  ([Rory Sutherland](http://www.ted.com/talks/rory_sutherland_life_lessons_from_an_ad_man.html)
  This is another perspective on the idea that "the medium is the
  message".

**What can we learn from?**

**Who is working on this?  Which aspects are there too many people
working on?  Which aspects are there too few people working on?  What
are some ideas I can bring in from left field?** MIT Media Lab.

**Corporate environments versus academia:** It's interesting to think
  about the environments in which one can do this kind of work.
  Corporations are usually design to take prototypes and turn them
  into products.  Academia funnels people toward a few areas deemed
  fashionable (often for spurious reasons), and draws the
  highest-expertise people out of work at the coalface.  This is not a
  recipe for success.

**Why aren't corporations good at the full prototype-product
  pipeline?**

**What is an explanation?**

**What is a document?**

# Cognitive tools and super-realist art

_This material is adapted from an essay I wrote about super-realist
art_

Let me show you an example where super-realist art is used to change
how people think:

<iframe width="640" height="480" src="http://www.youtube.com/embed/hVimVzgtD6w#205" frameborder="0" allowfullscreen></iframe>

Listen to the audience cheer and whoop at 5:02.  The presenter, Hans
Rosling, has taken four decades of United Nations' data about family
size and life expectancy in different countries, and animated the data
so we can see it change over time.  Sounds simple enough.  But by
presenting the data in this way, Rosling enables the audience to make
a startling discovery.  Most people in the audience, I expect, grew up
believing that there is a sharp distinction between rich and poor
countries, that people in rich countries live much longer, and have
much smaller families.  Certainly, I was brought up with this story.
What the video reveals is that while this story was true in the 1960s
and 1970s, it is no longer true.  The world has changed dramatically,
and we are challenged to rethink what we believe.  Even if we suspect
the video is misleading, the onus is on us to explain why it's wrong,
and what evidence we have for an alternate view of the world.

Rosling's video is super-realist art, revealing a previously hidden
world.  But it also changes how we think, and so it's also a cognitive
tool.  You may perhaps worry about whether it's the video itself which
is a cognitive tool, or is the cognitive tool really the software
which Rosling used to analyse the data and create the video? In fact,
the distinction is more subtle than it first appears.  The video was
perhaps constructed through dozens of intermediate iterations,
experimenting with many different ways of representing the data.  Each
of those iterations informed the thinking that went .  And so for the
most part I won't try to make clear separation between cognitive tools
and their outputs.

Cognitive tools and super-realist art are closely related.  They're
not the same --- a calculator is a cognitive tool, but it would be a
most unusual calculator that could be considered (or which produced)
super-realist art.  However, consider examples of super-realist art
such as the light-in-a-bottle, _Water in Suspense_, and the Hubble
Extreme Deep Field.  Each vividly represents new aspects of reality.
Each suggests many questions.  Personally, I've found that they've
each changed how I think about light, about water, and about the
Universe.  And so these pieces of super-realist art are also cognitive
tools.

This is not to say that the _point_ of super-realist art is to create
cognitive tools.  A Hollywood movie mogul of old --- some say it was
Samuel Goldwyn --- supposedly rejected a moralizing movie script with
the words: "If you want to send a message, send a telegram".  Taking a
similar stance, artists such as Juan Geuer often create art that is
principally for art's sake.  The purpose of Geuer's _Water in
Suspense_ is not to provide us with a new tool for thought.  Rather,
it is to reveal an unsuspected beauty inside a drop of water.  It is
fortuitous that it also stimulates new ways of thinking about water,
but it is not the point.  By contrast, Rosling's software is primarily
a cognitive tool, enabling new ways of thinking. It uses beauty as a
vehicle, and so it also produces super-realist art, but this is not
its primary purpose.  And so while super-realist art and cognitive
tools overlap, we should analyse them on separate grounds.

I find the creation of new and better cognitive tools inspiring.  It's
something I'd like to contribute to.  And so I will conclude this
essay with two heuristics which both help make better cognitive tools
_and_ making better super-realist art.

**Radical concreteness:** The first concerns a heuristic I call
_radical concreteness_.  To explain radical concreteness, let me
describe another cognitive tool and super-realist art piece, the
computer game [http://braid-game.com/](_Braid_).  One of the
best-selling computer games of 2008, _Braid_ appears at first glance
to be a standard platform game.  It uses many common elements of the
platform genre: there are puzzles to be solved, and six worlds to
explore.  But _Braid_ has a beautiful twist.  Each world gives the
player the ability to manipulate time in a different way.  It might be
a simple ability to rewind time.  Or perhaps to slow time down.  Or
some more complex manipulation.  Furthermore, the puzzles are
ingeniously designed so that their solution requires you to manipulate
time in just the right way.

The psychological effect of playing _Braid_ is remarkable.  My
professional background is as a theoretical physicist, and like many
theoretical physicists I've thought about different models of time.
But _Braid_ pushed my thinking further. It immerses you in concrete,
vividly rendered models of how time can be altered.  And success in
the game demands that you internalize those models.  I found myself
_dreaming_ about new models of time.  Braid was a cognitive tool to
help thinking about time.

What makes Rosling's animation and _Braid_ so powerful is that they
make vivid and concrete what would otherwise be vague and abstract.
It's tempting to phrase this as a heuristic: "develop representations
which are as vivid and concrete as possible".  The problem with this
heuristic is that it's not strong enough.  It's an easily-ignored
platitude.  What examples like Rosling's statistics and _Braid_ really
show is that we routinely and dramatically underestimate how vivid and
how concrete representations can be made.  We look at the UN
statistics, and see only a table, or perhaps a few graphs.  We don't
challenge ourselves to find a way of showing the data that would cause
an auditorium full of people to erupt in wild cheering.  Or we think
about models of time, and play with them mathematically, but never
imagine that if put into the right form we'd start to see them in our
dreams.  It's a failure of the imagination.  And so we can say, with
only a little dramatic license: _you can **always** find a way to make
your representation more vivid and more concrete_.  This is a doctrine
of _radical concreteness_.
    
Let me give you an example where I think this idea of radical
concreteness could be pushed much further.  In October of 2012, a team
of researchers at MIT announced that they've developed a
[game](http://gamelab.mit.edu/games/a-slower-speed-of-light/) which
show what it's like to live in a world where the effects of relativity
are obvious.  The idea is to reduce the speed of light to the kind of
velocity we're familiar with in the everyday world, so that it's
possible to see effects such as time dilation, length contraction, the
Doppler effect, and so on.  By playing the game, you begin to build up
intuition about what it's like to live in a relatavistic world.

I won't show you the game trailer (see the game link above).  Frankly,
the trailer doesn't make it so easy to see the relativistic effects.
Instead, I'll show you an older visualization developed by XXX and
XXX.  It shows what it's would be like to drive down a highway, if the
speed of light was much slower. The video is a bit fuzzy, but stick
with it:

<iframe width="640" height="480" src="http://www.youtube.com/embed/JQnHTKZBTI4?rel=0" frameborder="0" allowfullscreen></iframe>

In worlds like these you can actually *experience* what it's like for
time to dilate, for space to contract, and so on. And it's easy to
imagine games which, like _Braid_, would push this idea a long way.

We can go further.  In 1994, a scientist named
[Miguel Alcubierre](http://en.wikipedia.org/wiki/Miguel_Alcubierre)
[announced](http://arxiv.org/abs/gr-qc/0009013) to the world that he'd
discovered a _warp drive_.  Now, of course, you've no doubt heard that
it's impossible for objects to travel faster than light.  This is
based on a result of special relativity, which shows that
faster-than-light objects could be used to violate causality.
However, special relativity is really an approximation to a deeper
theory --- general relativity.  Alcubierre was a specialist in
studying simulations of general relativity, and he'd built up a lot of
intuition about how spacetime behaves.  He used that intuition to find
a solution to general relativity with the remarkable property that an
object could move faster than light (when viewed in the usual frames
of reference), without any violation of causality occurring.

I won't try to describe.  But after I'd read about both Alcubierre's
drive, and XXX and XXX's simulations of relativity, it started me
wondering.  We've seen lots of games that let people design levels or
design dungeons.  Why not a game that lets people design their own
spacetimes?  It'd be challenging to make the game fun --- there's no
doubt players would need warming up.  But I'll bet it could be done!
After all, one of the most popular games of all time was about time
travel.


**Multiple representations:** One of the people who is think hard
about cognitive tools is Bret Victor.  In a remarkable presentation
made in 2012, he develops a single, simple principle: it should XXXX.
This sounds simple, but has many consequences. Take a look at the
following video from XXX to XXX where he shows what this principle

XXX

Like any powerful principle, Victor's principle is generative.  It can
be applied to a large number of different .  He shows how it can be
applied to XXX.  To XXX.  And it's easy to think of.  I imagine myself
as CEO of PIxar, and asking what would I do?  An obvious application
is to wonder: should we buy ourselves enough computing power that
artists can see their designs rendered in near real-time?  Yes, it
would cost a lot --- but it would also totally transform the artist's
work experience.  Would it be worth it?  I don't know.  But it's 

I'd like to explore beyond Victor's principle.  Lots of things have
multiple representations.  And we get power by understanding how those
representations relate.  So you can generalize Victor's principle:

> 


## Problem: understanding complex tools:

How should we understand a model with a trillion parameters?  We
*have* these kinds of models.  Google's translation service uses
incredibly complicated models of human language.  In some ways Google
knows more about human language than any one person.  But how can we
make sense of the model?  And we're getting lots of such models.  My
guess is that we're ultimately going to end with mighty towers of
tools: trillion parameter models which will get re-understood as
million-parameter models, which can then be understood in sixteen
hundred different ways.


My instinct here is right.  What do we currently have trouble with
doing?  Where are the current limits where we'd like to pull our
cognition futher?


## Notes on relevant papers

David H. Jonassen and Thomas C. Reeves, "Learning With Technology:
Using Computers as Cognitive Tools": Alternate terms include cognitive
technologies, and technologies of mind.  What's the difference between
this point of view and computer software as media?  It's not so clear
to me that there is one, except in the sense that tools aim to make
certain tasks easy that were formerly hard, while media aims to do
something entirely different (communication).  This paper is obviously
within the area of educational research.  One perspective that seems
really badly lacking from this area: students as independent entities
with dreams and goals of their own.  If they don't align with the
tools, then there's no way the tools can matter.  Places a lot of
emphasis on constructivist versus instructivist models of learning; I
think desire-based learning is much more important.  A curious fact:
it's not clear from the paper what success would look like.  A very
interesting obervation: tools most effective when they involve us in
designing our own representation of knowledge.

Wouter van Joolingen, "Cognitive tools for discovery learning" (1999).
Another educational article.  

## To read

Papert

# Essay

Suppose someone asks us to multiply 73 by 36 in our head.  If we're an
ordinary person, chances are that it'll be a struggle.  But, if we're
given a pencil and paper, all of a sudden we can do it easily.

Familiarity makes us take this for granted.  But if you were viewing
it from the outside, for the first time, it would appear quite
remarkable, as though the pencil and paper had somehow granted the
person doing the multiplication magical powers.

It's not just the pencil and paper which make it easier.  If you give
the pencil and paper to an untrained person, chances are that it will
help only a little with the multiplication.  

No, what makes it easier is pencil, paper, and an \emph{idea} --- the
multiplication process which most of us learn in school.

In fact, there are many variations on the multiplication process.  And
some variations make the multiplication easier, while others make it
harder.  In other words, how much easier multiplication becomes
depends on the quality of the idea.

The question I want to address: what makes a good cognitive tool?

*A priori* we don't have a good instintive feeling for what makes a
 good cognitive tool.


What we'd really like is two things: (1) a *predictive theory* which
tells us what effect a particular cognitive tool will have; and (2)
design principles that make it easy to find cognitive tools which have
particular desired impacts.

We've made a start on these things with (on the academic side) the
study of human-comuter interaction and computer-supported co-operative
work, and (on the commercial side) design and marketing.  But we a
long way from a truly predictive theory.

Here's the
example:

>   123
> x 456

Using the grade school multiplication algorithm, I start by
multiplying the rightmost digits of both numbers, i.e., 6 by 3.  This
gives me 18, so I write down 8, and "carry the 1":

>   123
> x 456
>   ---
>     8 carry 1

Incidentally, the way I was taught the multiplication algorithm in
school, it was usual to write the carried digit as a superscript to
the left of the 8.  I haven't done that here, because it's
inconvenient.  I'll come back to this point a bit later.

The next step of the procedure is to multiply the rightmost digit of
the bottom number (6) by the second-to-right digit of the top number
(2).  That gives us 12, to which I add the carried result (1), to get
a total of 13.  So I write down 3, and again carry the 1:

>   123
> x 456
>   ---
>    38 carry 1

Then I multiply 6 by 1, and add the carried digit, to get 7, with
nothing carried.

>   123
> x 456
>   ---
>   738

Next I do essentially the same procedure, but for the 5 in 456.  It's
very similar, with lots of single-digit multiplication, carries, and
additions.  The final result is:

>   123
> x 456
>   ---
>   738
>  615

And then finally I do it for the 4 in 456:

>   123
> x 456
>   ---
>   738
>  615
> 492

Then we add the three rows below the "---". I won't explicitly write
out all the operations involved --- they're along much the same lines
as before.  But we get a final result:

>   123
> x 456
>   ---
>   738
>  615
> 492
> ---
> 56088

