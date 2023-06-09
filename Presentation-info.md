Introductions: Jez Asma Rachael

Intro: Jez

Our project is about learning facts using virtual flashcards. This MVP will
focus on spellings, which I had already worked with for many years, but our aim
is for this to be a tool for learning Japanese, which is one of Rachael's
passions, and so it has been given a smart Japanese theme.

As long ago as the 1880s, Hermann Ebbinghaus was showing how sequences of
information can be learned by being exposed to them and then recalling them
(Ebbinghaus, H (1885/1962) _Memory: A contribution to experimental psychology_,
New York: Dover), and this is what our flash cards enable.

Ebbinghaus concluded that the most effective way to learn facts was to revisit
them at intervals, which increase after each learning. So for best results, use
our flashcards again after half a day, a full day, three days, 6 days, 12 days
and 24 days. Or more often, if you like.

In terms of spelling we know that students, with supportive instruction, are
capable of learning to develop and use a combination of phonological,
orthographic and morphological strategies from the earliest years of school
(Critten et al 2013, Daffern 2018, Treiman & Kessler 2014).

But not every word can be spelled with this knowledge, and many of us struggle
with words with multiple “tricky bits”.

Albert Einstein said: “I cannot write in English, because of the treacherous
spelling. When I am reading, I only hear it and am unable to remember what the
write word looks like”.

Research tells us that practising and learning words is likely to improve
spelling competence, and if this is combined with the strategies above, the
likely improvement is significant (Fisher et al, 2007). Therefore our flashcards
provide cues about tricky bits and where morphology can also help.

In time, we would like to add new languages and explore what other content can
be practised in this way and we have undertaken research into applying it for
instance to javascript syntactical items.

Disclaimer: We recommend this process for learning facts which are hard to
remember but which are understood. By far the most important aspect of learning
is understanding how facts are connected, and this must always come before any
form of rote learning. It is also worth remembering that Einstein _also_ said:
“Education is not the learning of facts, but the training of the mind to think”.

### User stories

- I am a user that wants to learn to correctly write commonly mispelled words
- I am a user that wants to practise spellings using my phone
- I am a user that wants to know which words I have spelled wrong when
  practising  
  We also considered _these_ for future features:
- I am a user that wants to upload my own words to practise
- I am a user that wants to use spaced retrieval to learn spellings
- I am a user that wants to learn vocabulary in another language

### Our problem domain

- How to imitate flash cards so the user can read the card, turn the card over
  and then try to write the target word.
- How to allow the user to write the word sometimes without seeing the word.
- How to ensure that the correct spellings are achieved in every session, and
  that misconceptions or misspellings are not allowed to remain beyond the
  session, by repeating at intervals until they are correctly written.
- How to enable the user to see which words had caused problems.
- How to enable users to input their own content to practise.
- How to adapt this to languages eg Japanese
- How to adapt this to code eg javascript syntax items

### Technical problems

- Changing css animation from a hover trigger as we found it on w3schools to a
  click trigger was awkward and so was adjusting borders and margins
- CSS animation for flipping a card and making sure it flipped at the right
  times: it turned out to need more controls after the MVP stage was reached
- version management: sharing out tasks and then merging the outcomes is tricky
  when the code overlaps eg in style.css or bug fixing

- Future challenges:
- - Add a switch to toggle text-to-speech on and off
- - Add a page to allow uploading of user's own spellings and other content
- - Add lists for different languages (maybe include examples in MVP?)
- - Managing different learning content: it will be hard to make fields on card
    adapt to different info like languages

Things to have open:

- VS code
- live server
- trello board
- wireframe - google jamboard

## Domain modeling: Summary

Domain modeling is the process of creating a conceptual model for a specific
problem. And a domain model that's articulated well can verify and validate your
understanding of that problem.

Here's some tips to follow when building your own domain models.

1. When modeling a single entity that'll have many instances, build
   self-contained objects with the same attributes and behaviors.
2. Model its attributes with a constructor function that defines and initializes
   properties.
3. Model its behaviors with small methods that focus on doing one job well.
4. Create instances using the new keyword followed by a call to a constructor
   function.
5. Store the newly created object in a variable so you can access its properties
   and methods from outside.
6. Use the this variable within methods so you can access the object's
   properties and methods from inside.

#### What Does The Program Do?

(<a href="https://rkay301.medium.com/programming-fundamentals-part-two-the-problem-domain-how-to-design-a-program-application-4faf0a5753f8">https://rkay301.medium.com/programming-fundamentals-part-two-the-problem-domain-how-to-design-a-program-application-4faf0a5753f8)</a>  
The first step in determining the Problem Domain of a program is to ask yourself
what your application is supposed to do. Since the goal of this series is to
show you the process of thinking about, designing, and building programs, we
will choose a very simple problem for our hypothetical program to solve. For
this series, we will build a simple binomial expression calculator.

The first step in designing any program is to start by explaining what it does
in simple, written language. The technical term for this written explanation is
a “Problem Statement.” Now, as a complete beginner, I recall being worried about
whether or not my problem statements were perfect or not, and the truth is that
trying to determine the perfect problem statement (and by extension, problem
domain) on your first try, is a fool's errand.

Instead, use this process as a starting point which can be refined as new ideas
(or roadblocks) pop up during the design and build process of your program.
