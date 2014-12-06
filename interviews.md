---
layout: default
title: Technical Interviews - Project Intern
permalink: /interviews/
---
# Technical Interviews

There are a ton of resources for this on the internet.

At a high level, the interview is really meant to be a conversation to access:
- If you can fit in as a "peer", based on your ability to take part in technical
  discussions and to converse on some level with your interviewer.
- How well you measure up against other candidates. _Are you good enough?_
- Whether you are someone they'd want to work with.

It will be expected of candidates to have the following set of knowledge
(non-exhaustive list):

- Basic programming skills (able to write code)
- Appreciation for computation semantics - primitives, combination,
  abstractions, even if implicitly
- Algorithms and Data structures - you're expected to have completed and have
  scored well in the algorithms and data structures course, or have the
  equivalent knowledge
- Sensibility in systems design and database design - understanding the
  trade-offs
- Know at least one programming language well, and ability to pick up a new
  language on the fly
- Basic knowledge in logic, formal systems, and proof systems
- General problem solving skills

## Conduct
While most companies differ in their interviewing style and approach, there are
some common patterns across the board.

Most interviews last from 45 minutes to an hour.

Outline of a typical interview:

0. Intro, soft questions
1. Actual questions (usually only one) - the bulk of time is spent here (30 - 45
  mins)
2. Q&A - you get to ask questions here.


## Question types

There are 4 major types of question an interviewer may ask:

1. __Design__ - you'll be asked how you'd design a particular feature (the
   back-end, the database etc.). For instance, you may be asked how you would
   implement a simplified version of Facebook's news feed.
2. __Coding Question__ - You will be given a problem and you'll be asked to
   implement the solution. While algorithmic questions are highly likely, an ad
   hoc type of question may also be possible. Sometimes an interviewer wants to
   assess your basic coding ability or your familiarity with one specific
   programming language that you may have claimed you were familiar with (e.g a
   pointer specific question in C/C++).
3. __Test Question__ - You may be asked how you'd test a particular feature or
   code.
4. __Logic Puzzles__ - Brainteasers are increasingly becoming less common but
   they still exists.

### Here are some example questions

#### Soft Questions
- Tell me about a project that you've worked on that's technically challenging
  and walk me through your problems and how you solved them
- Tell me about yourself
- Tell me about X (where X is found on your resume)

#### Soft Questions (Culture fit)
- Do you use our product? What do you love about it and why?
- Why do you want to join X? (where X is the company)

#### Technical Questions (Short, Recall)
- What is `0x05` + `0x1a`?
- What is a deadlock?
- What is the runtime of the various operations of a hashtable?
- What is the difference between a process and a thread?

#### Technical Questions (Non-coding)
- Explain to me what happens when I type "google.com" into the address bar
- Design a url link shortening service.

#### Technical Questions (Coding)
- Find an element in a sorted, pivoted array
    - Pivoting a sorted array: `[1, 2, 3, 4, 5]` => `[4, 5, 1, 2, 3]`
- How many ways are there to buy a given amount of coke if they come in the
  following sizes: 1, 6 and 24?
    - `7 => [1, 1, 1, 1, 1, 1, 1], [1, 6] => 2 ways`
- Implement a stack with an additional `#min` method that returns the min
  element in constant time.


_Don't worry if the questions above seem hard or foreign. Interviewers were
college students before and they know how much you are "supposed" to know based
on the classes you've taken._

## Some Tips and Advice

### Practice practice practice
Contrary to some of the advice you might find on the internet. You really should
practice technical interviews and not go into your first one cold. It helps more
than you can imagine.

Don't just read questions and their answers off the internet. Get a friend, a
senior to interview you. Prepare for it like you would the real thing and go
though the motion.

### Be fresh and ready for the interview
Don't underestimate any interview. Even a phone screen. Your interviewers will
probably expect you to bring your best self to the interview so make sure you're
fresh and ready for it.

### Soft questions
While not super critical, soft questions tend to start the interview. You won't
want to get off to a bad, stuttering start do you?

### Think before you speak
No one expects you to parse the question the first time. No one expects you to
respond immediately. When given a question take a few seconds to think before
speaking. Jumping to conclusions is really bad and reflects badly on you.

A typical scenario:

- Interviewer: "What is the run-time of your solution?"
- Candidate: "`O(n)`"
- Candidate: "Oh. wait."
- Candidate: "Erm, `O(nlogn)`"
- Candidate: "jk. O(n)"

Breath, relax and think before you speak.

### Clarify any doubts
This is really about communication skills. When asked an ambiguious question, do
you simply assume something is the case? You can and should always ask the
interviewer to repeat stuff, to give examples, input/output to problems etc.

### There are usually trade-offs involved
The aim of the interviewers is to assess your competency as an engineer in the
short amount of time they have. Part of engineering is understanding and being
able to weigh trade-offs involved in engineering decisions. For instance, you
may be asked to implement an abstract data-type that can store data (perhaps
something that emulates the behavior of an array). You may simply start with an
array, to which you face a problem when your static array runs out of size. You
may then change it to a linked-list, and you realize there are issues with
fragmentations. Here, there are trade-offs and while the interviewer may guide
you through it, it helps if you are mindful of them to begin with.

### Be mindful of the assumptions you're making.
This applies to all types of problems (design, coding, etc.) For instance, when
asked to implement a routine, it may be convenient to make assumptions like the
validity of the argument values passed in. While this is generally a reasonable
assumption to make, it doesn't hurt to check and to practice defensive coding in
your implementation.

### Don't underestimate simple problems
Do not underestimate problems that appear simple. Always assume that the
interviewer is an experienced interviewer, and has a specific intent in giving
you this problem. It may be that there are corner case traps that you were not
careful of, or that there are even more efficient solutions that you did not
think of. It could also be that the interviewer wants to see how elegant your
coding is.

After all, much of a software engineer's work is to implement routines and
modules that are not that complicated, but in an elegant, concise and
maintainable manner.

That said, do not overthink when given a simple problem. It could simply be a
warm-up problem or a necessary building block to other problems.

### Articulate your thoughts clearly
This is really important. The whole interview should be seen as a conversation
with the interviewer and to allow him/her to understand you better. When you're
stuck, don't be too afraid of asking for help (of course, you should spend some
time thinking through the problem yourself first).

Its really hard to evaluate a candidate that doesn't speak or explain his/her
thoughts. Getting the correct answer is only part of the process. How you get
there is way more important and useful for evaluation purposes.

### Code should compile
This is a simple rule: always err on the side that your interviewer has worst
OCD. You won't want to come across as sloppy, would you? This includes
semi-colons, braces, indentation, syntax _(its not that hard)_. Unless
explicitly stated, always use a proper language, not pseudocode.

### Test proactively
Do you test your code? The interview should be no different. A typical mistake
people often make is that they simply stop after they've written down the
solution. Don't stop there, test it, check for edge cases, this shows your
interviewer what kind of an engineer you will be if they hired you.

The way I usually go about doing this, is once I'm done, I'll say something
like: "I'm going to step through my code now to make sure I didn't make any
obvious errors". I'll then list down the testcases (input/output) that I'll be
using and meticulously step through every line, every variable assignment...

### Think of questions for ask the interviewer
This is a no-brainer. It demonstrates interest in the job. Do some research and
have a couple of questions ready to ask at the end of the interview.
Remember, the interview works both ways.
