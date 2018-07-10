<!--

themes I like:
business class #2

ostrich grey & pink
or white (and adjust highlight color)        


TODO
- check mine and maxes notes from open source bridge
- grab theme from pink laptop, how to share themes between computers?
- fix random fucking captializations
- talk about beyond PEP8
- more python and vs code stuff
- check speaker notes in powerpoint
- watch original talk and take notes

- talk about pre-commit hooks, include code

- mention pulling down the review to your own computer

Notes:
Talk a little bit about why we want to code review
have you thought about why you do it, besides for my boss told me so, or it's a habit on my team?

Look up interesting VS Code feature that can help
- integrated github pull requests in vs code
- live screen sharing
- format on save (i.e. with black)

think about less slides, how to condense them

Add bit about checking in with yourself. Have you eaten, gotten enough to drink? Do you need a walk? Are you stressed?

-->

# How to successfully grow a code review culture
## @nnja
## Nina Zakharenko

---

# What we'll learn today
- What are the benefits?
- Our Code Review Process
- How to Grow a Culture

---

# What we'll learn today
- How to be a Great Reviewer
- How to a be a Great Submitter
- Using Code Review to Build a Stronger Team

---

# Not one size fits all!

- team size
	- 2 vs 10
- product type
	- agency vs in-house
- defect tolerance
	- jet engines vs mobile games

--- 

# [fit] Why Code Review?

---

# [fit] Code Reviews Can <br> Be Frustrating
![](https://i.redd.it/06mc6ezq8uiz.jpg)

---

# Apparent Code Review Frustrations

 - Adds time demand
 - Adds process
 - Can bring up team tensions
 - “smart” devs think they don’t need it

---

# How do you get people to change the way they work?

# By showing them crystal clear benefits

---

# Find Bugs & Design Flaws

 - Design flaws & bugs can be identified and remedied before the code is complete
 - Case Studies on Review:
 - ⬇ bug rate by 80%
 - ⬆ productivity by 15%

 [.footer https://blog.codinghorror.com/code-reviews-just-do-it/]

---

# The goal is to find bugs **before your customers** do.

----

# Shared Ownership

 - We’re all in this together
 -  👀 results in positive motivation
 -  Overall increase in code quality
 -  No developer is the only expert
 -  Developers gain familiarity with modules via Review
 -  Decrease the “I Quit" Factor

---

# I Quit Factor? 
- concentrated specialized knowledge
- will one person sabotage the project if they left?

---

# Leave a Paper Trail
 - Code Reviews add a wealth of knowledge!
 - Why was a particular decision made?

---

# Code Review Benefits?
- Find Bugs
- Shared Ownership
- Shared Knowledge
- Reduce Bus Factor
- Leave a Paper Trail

---

# I've become a much better programmer by participating in code reviews

Process?

- GitHub (lots of other tools exist)
- GitHub reviews (this was so painful before they existed)
- Blocked merging (can't merge without a green check)

---

Grow  a culture

---

# It starts with a commitment

- Make a commitment to always Review before Merge
- Present the Facts
- Don’t force it
- New ideas take time to root

---

# Code Reviews need to be Universal

- Doesn’t matter how Senior / Junior you are
- Only Senior Devs reviewing == bottleneck
- Inequality breeds dissatisfaction
	- Break down old barriers and status quos

---

# Code Review is done by your **peers, not management**.

---

# Consistent Code

- Your code isn’t yours, it belongs to your Company
- Code should fit your company’s expectations and style, not your own.
- Reviews should encourage consistency for code longevity

---

# Style Guide

- Distinguishes personal taste from functionality
- Should be agreed upon before hand
- Great Codebases are written by a team, look like they were written by an individual.

---

# Consistent Code is **Easier to Maintain** by a Team

---

# No Blame Culture

- Failure is inevitable
- Mistakes become team, not individual responsibility
- Needs management support

---

# Blameless Post Mortem

- Meet shortly after Incident Resolved ◉ Understand the root cause
- Document how it was fixed
- Identify how to prevent it in future

---

For a blameless culture, don’t **point fingers!**

---

# When code reviews are part of the culture, people don’t expect their changes to be reviewed, **they want** their changes to be reviewed.

---

# Let's Review: How to Grow Culture?

- Make a Commitment
- Universal Code Review
- Performed by Peers
- Style Guide for Consistency
- Starts with No Blame Culture

---

# How should we code review?

--- 

# #1: Be a great reviewer.

---

# Have Emapthy.

<!-- TODO insert comic here -->

---

# [fit] Be Objective

# “**this** method is missing a docstring”<br>
# _instead of_ <br>
# “**you** forgot to write a docstring”

---

# [fit] Ask Questions Don’t Give Answers

- “Would it make more sense if... ?”
- “Did you think about... ? ”

---

# [fit] Offer suggestions

- “it might be easier to”
- “we tend to do it this way”

---

# [fit] Avoid these terms

- Simply
- Easily
- Just
- Obviously
- Well, actually...

---

# [fit] ... now, simply

<!-- TODO insert image -->

---

# [fit] Have Clear Feedback

- Strongly support your opinions
- Share **How & Why**
- Link to supporting blogs, stackoverflow examples, or documentation.

---

<!-- TODO: maybe insert an example of feedback that's not clear -->

---

# Compliment good work and great ideas

<!-- TODO insert image -->

---

# Don't be a perfectionist


<!-- TODO insert image -->

---

# Don’t be a Perfectionist

 - For big issues, don’t let perfect get in the way of perfectly acceptable.
 - Prioritize what’s important to you.
 - Usually 90% there is good enough.

---

# It’s OK to Nit-Pick

 - Syntax Issues
 - Spelling Errors
 - Poor Variable Names
 - Missing corner-cases
<br>
 Save the nit-picks for last, after any pressing architecture, design, or other large scale issues have been addressed.
 
 
---

# Avoid Burn-Out

## Studies show reviewer should look at 200-400 lines of code at a time for maximum impact

<!-- TODO chart -->

footer: https://smartbear.com/learn/code-review/best-practices-for-peer-code-review/

---

# Avoid Burn-Out

Limit Reviews to 200-400 lines between 60 and 90 minutes, then take a break.

<!-- TODO chart -->
 
footer: https://smartbear.com/learn/code-review/best-practices-for-peer-code-review/

---

# Do Reviews in 24-48 hours

<!-- TODO: Still waiting meme -->

---

# Define Done

 - Let the submitter know if you approve, or if you’re waiting for changes.
 - Use consistent language
	 - LGTM or Awaiting Changes
 - Follow up when the submitter says they fixed something

--- 

# [fit] How can we be a Great Reviewer?

- Have Empathy
- Watch your Language
- Have Clear Feedback
- Give Compliments
- Don’t be a Perfectionist

---

# [fit] How can we be a Great Reviewer?

 - Avoid Burn Out
 - Complete in 24-48 hours
 - Define Done

--- 

# Be a Great Submitter

---

<!-- TODO insert comic -->

---

# Don’t get rubber-stamped.

<!-- TODO image -->

---

# [fit] Don’t be clever.
# [fit] **Readability Counts!**

---

> Good code is like a good joke.
It needs no explanation.
- Russ Olse

---

Stages of Review

**0:** before submission
**1:** submitted
**2:** (optional) work in progress (30-50%)
**3:** almost done (90-100%)
**4:** review completed

<!-- TODO this slide is confusing -->

---

# [fit] step 0:# [fit] before submission

---

# [Fit] Provide Context (The Why)

- What was the motivation for submitting this code?
- Link to the underlying ticket/issue
- Document why the change was needed ◉ For larger PRs, provide a changelog
- Point out any side-effects

---

# [fit] **YOU** are the# [fit] Primary Reviewer

 - Review your code with the same level of detail you would give giving reviews.
 - Anticipate problem areas

--- 

# [fit] The Primary Reviewer

- Make sure your code works, and is thoroughly tested.
- Don’t rely on others to catch your mistakes.

---

# Before submitting, try a checlist

<!-- TODO image -->

---

# [fit] ☑︎ small stuff

- Did you check for reusable code or utility
methods?
- Did I remove debugger statements?
- Are there clear commit messages?

---

# [fit] ☑︎ big stuff

 - Is my code secure?
 - Will it scale?
 - Read the Checklist Manifesto

---

# [fit] step 1:# [fit] submitted

---

# You’re starting a conversation.

- Don’t get too attached to your code before the review process
- Anticipate comments and feedback
- Acknowledge you will make mistakes

---

# [fit] step 2 
# [fit] *(optional)*# [fit] work in progress

---

# [fit] Submit **Work in Progress** Pull Requests

- Necessary for bigger features
- Don’t be afraid of showing incomplete, incremental work
- Open them your code is 30-50% done
- This is the right time to get feedback on architectural and design decisions

---

# [fit] When Code is Work in Progress

Types of Feedback to expect:

- Architectural Issues
- Problems with Overall Design
- Design Pattern Suggestions

---

# [fit] step 3:# [fit] almost done

---

# [fit] When Code is Almost Done

- Feedback to expect:
- Nit Picks
- Variable Names
- Documentation & Comments
- Small Optimizations

^ This process prevents wasting time and effort for bigger, more complex pull requests.

---

# [fit] One Review per Issue

 - If you’re solving multiple problems, break them up into multiple PRs for ease of review.
 - Solved an unrelated problem? make a new PR with a separate diff
 - You can branch off your feature branch to keep the diff small

--- 

# Prevent Reviewer Burnout

- Remember, reviews lose value when they’re more than 500 lines of code.
- Keep reviews small and relevant.
- If submitting a big review is unavoidable, give the reviewer extra time.

footer: https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/bosu2015useful.pdf

---

# [fit] ✔ Check Code# [fit] with **Automated Tools**

---

# [fit] ✔ Linter

check syntax or style guide violations

<!-- TODO include screenshot -->

---

# [fit] ✔ Tests

 - Write tests!
 - Don’t know code health if tests are failing
 - Tests Identify problems immediately

---

<!-- TODO scumbag programmer image -->

---

# [fit] ✔ Continuous Integration

automated build with every push

<!-- TODO Travis image -->

---

# [fit] ✔ Coverage

% of code execute when running a test suite

<!-- TODO coverage report screenshot, and maybe talk more about coverage.py -->

---

# [fit] ✔ Coverage

- Coverage tools can integrate into GitHub
- `coverage.py`
- [coveralls.io](http://coveralls.io)

<!-- TODO coverage.py or coveralls screenshot -->

---

# [fit] step 4:# [fit] review complete

---

# [fit] Be Responsive

 - Reply to every comment ◉ Common Responses:
 	- Resolved
 	- Won’t Fix
- If you won’t fix, make sure you’ve come to a mutual understanding with the reviewer

---

# [fit] It’s still a Conversation

If there were comments, let your reviewer know when you’ve pushed changes and are ready to be re-reviewed.

---

# [fit] Don’t Bike-Shed

- bikeshed.com
- back & forth > 3 times? step away from the
keyboard
- talk instead!
- record the results of the conversation in the Review

---

If you're co-located, great. Walk to the other person's desk.

If you're not, use vs-code live share. 

---

# Fight for what you believe, but **gracefully accept defeat.**

<!-- todo image -->

---

# Don’t take feedback personally. It’s an **opportunity for growth.**

---

# [fit] How to be a Great Submitter?

 - Provide the Why (context!)
 - Review your own code
 - Expect Conversation
 - Submit in progress work

---

# [fit] How to be a Great Submitter?

- Use automated tools
- Be Responsive
- Accept Defeat

---

# Code Reviews Build a Stronger Team

^ code reviews sound like hard work, and they are. but now you can reap the rewards
^ Use that as an advantagewhen someone new joins!

<!-- TODO image -->

---

# First day vibes...

<!-- TODO no idea what I'm doing meme -->

---

# [fit] Newbies


- Not everyone has experience being reviewed.
- Remember what it felt like when you introduced the process.
	- Ease into it!

---

# [fit] On-boarding

 - The first submitted review is always the hardest
 - Start by reading recently completed reviews
 - First review should be small.
 - Share the style guide

---

# [fit] Everyone’s a Reviewer

 - Junior devs start by doing pair-reviews with a more experienced teammate.
 - Use it as a mentorship opportunity.


> “When your team succeeds, you succeed.”

<!-- TODO find a way to work in some of kate heddlesons blog post -->

---

> Hiring senior engineers is hard. You can hire junior engineers, and **grow them** into functional productive parts of your team.
- Sasha Laundy

---

# If you’re not doing code reviews, **you’re missing a big opportunity**.

---

# [fit] Remember...

 - Allocate the time
 - Develop, don’t force the culture
 - Not one size fits all
 - Or a one stop fix
	- Use in addition to tests, QA, etc for maximum impact

---

# What did we learn?

---

# reviews decrease WTFs/m the only valid measurement of code quality

<!-- TODO insert comic -->

---

# less WTFs ➡ happier devs!

<!-- TODO homer image -->

---

# Thanks! (TODO)

* twitter
* link to slides
* email

---

# [fit] Resources & Additional Reading
* [Microsoft Study on Effective Code Review](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/bosu2015useful.pdf)
* [Code Reviews: Just do it](https://blog.codinghorror.com/code-reviews-just-do-it/)
* [Code Project - Code Review Guidelines](http://www.codeproject.com/Articles/524235/Codeplusreviewplusguidelines%20and)
* [Great Example Checklist](http://insights.dice.com/2012/10/31/whats-on-my-code-review-checklist/)
* [Best Practices for Code Review](https://smartbear.com/learn/code-review/best-practices-for-peer-code-review/)
* [Rebecca's Rules for Constructive Code Review](https://storify.com/ReBeccaOrg/rebecca-s-rules-for-constructive-code-reviews)
* [My Big Fat Scary Pull Request](https://medium.com/@jdan/my-big-fat-scary-pull-request-2c8ac394540e#.yhs96vbxu)

---

# [fit] Example Style Guides
* [Python](https://www.python.org/dev/peps/pep-0008/)
* [Javascript](https://github.com/airbnb/javascript)

Google has many good, but strict style guides at: [https://github.com/google/styleguide](https://github.com/google/styleguide)

Doesn't matter which one you use. Pick one and stick with it.