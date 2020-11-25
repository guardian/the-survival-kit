# Brag about it: Writing a brag doc

_This is based on a [blog post by Julia Evans][] that is well worth a read in
addition to what is written here._

## What the heck is a "brag doc"?

A Brag Doc is a document you use to keep track of all your work that you do
throughout the quarter/year/period so that you can look back on it at the end
when doing reflective work and asking for feedback. As mentioned in the blog
post linked to above

> There’s this idea that, if you do great work at your job, people will (or
should!) automatically recognize that work and reward you for it with promotions
/ increased pay. In practice, it’s often more complicated than that – some kinds
of important work are more visible/memorable than others. It’s frustrating to
have done something really important and later realize that you didn’t get rewarded
for it just because the people making the decision didn’t understand or remember
what you did.

Being recognised for you work though isn't just about promotions or getting
raises (though these things are both still important). This document can also
help you reflect on what you learn and work on, the things that are important
to you, or where you'd like to go next.

## But why should I bother?

Let's start by considering some of the more specific reason for why it's worth
making a brag doc, and this should then help us understand what we want to put
in it.

### You won't remember everything you did

You're going to be doing so much in your job, both big and small, that
remembering all of it is going to be difficult, if not impossible. Maybe you
can go through a bunch of pull requests on Github. But what if you were pairing
on a piece of work? If you're lucky yopu'll have remembered to use
[co-authored-by commits][] to try and keep track of that work, but that won't
necessarily help with the Pull Requests or with work that isn't coding.
Maybe you'll rely on Trello boards or similar to capture that work but, again,
there will be so many times where some one-off mentoring or code reviewing would
go uncaptured that you'll fail to capture all the really important "other work"
that you do.

Instead, try make a habit of writing down all that work in your brag doc at the
end of the day/week. There are some great ways to build this into your routine
that I'll discuss below, but one of the key features of a brag doc is its
function in ccapturing __all__ of the work you do. So try remember to stick it
all in there!

### Your manager won't remember everything you did

This is basically a repeated of the previous, but with some added caveats.
There's a good chance that your line manager won't necessarily be on the same
team as you. Maybe you'll mention to them in your 1:1 sessions some of the work
you did, but without a written record they probably won't remember it all.
Working with your manager is one of the best ways to fat track your career and
your development, so making sure that they have an up to date reference of
everything you've been doing is a great way to facilitate this.

Remember to share it with your manager!

### your colleagues won't remember everything you did

__See above.__ (Feedback from colleagues is a key part of your development. Help
them out and do yourself a favour at the same time by sharing your doc with them
when it comes to feedback time.)

## Writing your brag doc

At its simplest, your doc is just a list of your accomplishments over the course
of your time in the job. So stick everything you do and everything you're
remotely proud of in it./ Presentations, focus group work, documentation,
mentoring, code review. Anything and everything should go in here. This might be
enough for you but if you want to get the most out of it it's worth doing a bit
more than that.

Build a bigger picture. What are you focussing on currently? Maybe you're
wanting to build out your understanding of client-side development and have
focussed on work around that. Or maybe you've tried really hard to tackle
accessibility or internal process, so there's more conceptual work happened
recently. By giving a general idea of what you're aiming for it helps you and
anyone else reading the document to understand why you've highlighted or
expanded on some work over others.

Try to notice patterns as you update your document. What kind of things are you
most proud of? What do you wish featured more in your day-to-day work? What
projects had the effect you wanted? What didn't work even if you're proud of it?
All these question can really help with breaking down that bigger picture and
with fleshing out the individual sections.

Finally, and arguably most importantly, __don't forget the fuzzy work!__ What is
"fuzzy work"? Fuzzy work is a lot of the work that you do that feels harder to
quantify. It's the kind of stuff that doesn't always feature on a Trello card or
that falls outside of your team's current weekly focus. This can include stuff like:

- Improving code quality or making code reviews a bit easier by establishing
some guidelines around coding style.
- Mentoring work.
- Doing code reviews for your team and others.
- Writing documentation! Everyone forgets how important this is because it
doesn't produce a fancy product at the end, but it's _really_ important.
- Getting rid of a bit of tech debt without it being part of a health week/healthcard.
- Design docs. Spending a few days sketching out your future work is really
important and will help the team and anyone else youwork with to understand what
you're aiming for.

As Julia Evans says in the original blog post:

> One way to approach this is to, for each goal:
>
>  1. explain your goal for the work (why do you think it’s important to refactor
> X piece of code?)
>  2. list some things you’ve done towards that goal
>  3. list any effects you’ve seen of the work, even if they’re a little indirect
>
> If you tell your coworkers this kind of work is important to you and tell
> them what you’ve been doing, maybe they can also give you ideas about how to
> do it more effectively or make the effects of that work more obvious!

### Where should I start?

Wherever you like! I'd recommend something digital because it's easier to share,
but after that it's really up to you. A Google doc is a good way to share it but
keep it semi-private. You could also just stick it in a Git repo. It might be
quite scary to make it (potentially) so public but, as long as none of the work
is confidential, you should be proud of it and it can really help if you ever
decide to move on from The Guardian and need evidence for interviews.

There are also some really fun ways of making this collabroative and supporting
your co-workers. Start a regular brag session where you and a few others get
together to update your brag docs and hype each other up. It can be a really
nice morale boost to be reminded of and praised for a piece of work you'd
forgotten all about. These are particularly useful around performance review
time when having someone to bounce off and work with can make the process of
self-reflection much less intimidating.

## Structure

There's a template linked to in the `templates/` directory that's a good starting
point, but I'll outline and add some context here as well.

_Below lifted directly from the [blog post by Julia Evans][]._

### Goals for this year:

List your major goals here! Sharing your goals with your manager & coworkers is
really nice because it helps them see how they can support you in accomplishing
those goals!

### Goals for next year

If it’s getting towards the end of the year, maybe start writing down what you
think your goals for next year might be.

### Projects

For each one, go through:

- What your contributions were (did you come up with the design? Which
components did you build? Was there some useful insight like “wait, we can cut
scope and do what we want by doing way less work” that you came up with?)
- The impact of the project – who was it for? Are there numbers you can attach
to it? (saved X dollars? shipped new feature that has helped sell Y big deals?
Improved performance by X%? Used by X internal users every day?). Did it support
some important non-numeric company goal (required to pass an audit? helped
retain an important user?)

Remember: don’t forget to explain what the results of you work actually were!
It’s often important to go back a few months later and fill in what actually
happened after you launched the project.

### Collaboration & mentorship

Examples of things in this category:

- Helping others in an area you’re an expert in (like “other engineers regularly
ask me for one-off help solving weird bugs in their CSS” or “quoting from the C
standard at just the right moment”)

- Helping new team members get started
- Writing really clear emails/meeting notes
- Foundational code that other people built on top of
- Improving monitoring / dashboards / on call
- Any code review that you spent a particularly long time on / that you think
was especially important
- Important questions you answered (“helped Risha from OTHER_TEAM with a lot of
questions related to Y”)
- Mentoring someone on a project (“gave Ben advice from time to time on leading
his first big project”)
- Giving an internal talk or workshop

### Design & documentation

List design docs & documentation that you worked on:

- Design docs: I usually just say “wrote design for X” or “reviewed design for
X”
- Documentation: maybe briefly explain the goal behind this documentation (for
example “we were getting a lot of questions about X, so I documented it and
now we can answer the questions more quickly”)

### Company building

This means “things you did to help the company overall, not just your project /
team”. Some things that go in here:

- Going above & beyond with interviewing or recruiting (doing campus recruiting,
etc.)
- Improving important processes, like the interview process or writing better
onboarding materials
- Working groups e.g. diversity, hiring etc.

### What you learned

Try listing important things you learned or skills you’ve acquired recently
(bonus points if you did a write up on it after)! Some examples of skills you
might be learning or improving:

- How to do performance analysis & make code run faster
- Internals of an important piece of software (like the JVM or Postgres or Linux)
- How to use a library (like React)
- How to use an important tool (like the command line or Firefox dev tools)
- About a specific area of programming (like localization or timezones)
- A new area like product management / UX design / software engineering
- How to write a clear design doc
- A new programming language

It’s really easy to lose track of what skills you’re learning, and usually when
I reflect on this I realize I learned a lot more than I thought and also notice
things that I’m not learning that I wish I was.

### Outside of work

It’s also often useful to track accomplishments outside of work, like:

- blog posts
- Talks/panels
- Open source work
- Industry recognition

I think this can be a nice way to highlight how you’re thinking about your
career outside of strictly what you’re doing at work. These things are not
compulsory though and you shouldn't feel pressured to do more than your
day-to-day work.

<!-- Reference links -->

[blog post by Julia Evans]: https://jvns.ca/blog/brag-documents/

[co-authored-by commits]: https://docs.github.com/en/free-pro-team@latest/github/committing-changes-to-your-project/creating-a-commit-with-multiple-authors
