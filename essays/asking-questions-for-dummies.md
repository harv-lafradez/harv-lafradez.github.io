---
layout: essay
type: essay
title: "Asking Questions For Dummies"
# All dates must be YYYY-MM-DD format!
date: 2023-09-07
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

<img width="500px" class="rounded float-start pe-4" src="https://3.bp.blogspot.com/-UN8Awz7zrNk/XIjLnX7El-I/AAAAAAAABvc/nfLh4oi7hoMklfu2CUZhXGWgQ8JMsXNWQCLcBGAs/s1600/mtbunnies250c.png">

## Getting started

We've all been there, wanting to ask a question in class without sounding stupid, but hesitating because we fear judgment. More often than not, it is through those moments that we truly ponder, "is this a dumb question?". There can only be one of two outcomes when dealing with this scenario, either your question is actually relevant and was also a question everyone else had, or your question was a dumb question and now you've embarrassed yourself in front of everyone. The latter is obviously undesirable, but have no fear! Asking the right questions does not have to be rocket science, and it sure does not have to be humiliating either.

## Let's learn by example

The ability to ask the right questions is one thing, but as growing programmers, learning to leverage online forums in a way that is helpful and not hurtful is paramount. A most notable tool at our disposal is StackOverflow, which is the premier online platform and community for programmers and developers, serving as a question-and-answer forum where people can ask technical questions related to programming, software development, and various technology-related topics.

A large community of programmers like ourselves have utilized this resource to ask their burning questions. Though, as you'll see in the upcoming examples of questions, one is desirable and the other is, well, not so much.

Let's take a look at this user's inquiry about the comparison operators of JavaScript:

```
Q: Which equals operator (== vs ===) should be used in JavaScript comparisons?

I'm using JSLint to go through JavaScript, and it's returning many suggestions to
replace == (two equals signs) with === (three equals signs) when doing things like
comparing idSele_UNVEHtype.value.length == 0 inside of an if statement.

Is there a performance benefit to replacing == with ===?

Any performance improvement would be welcomed as many comparison operators exist.

If no type conversion takes place, would there be a performance gain over ==?
```

As we can observe from this user's question, the heading itself proves to be useful for other programmers that may have the same inquiry as it is concise and uses keywords such as "equals operator" and "(== vs ===)" that novice programmers learning JavaScript are most likely to type into a search engine. This user ensures that they preface their question with a bit of context that elaborates on their thinking where in this case, this user includes their usage of JSLint (which is essentially a JavaScript syntax or style checker) and how its suggestions inspired their question whilst also providing an example. This user also follows up their initial question with other thought-provoking and discussion-encouraging inquiries that can prompt other more experienced users to engage in providing further insight beyond the scope of the simplicity of the original user's question itself. 

[This is the link to the question on StackOverflow.](https://stackoverflow.com/questions/359494/which-equals-operator-vs-should-be-used-in-javascript-comparisons)

```
A: The strict equality operator (===) behaves identically to the abstract equality operator (==)
except no type conversion is done, and the types must be the same to be considered equal.

The == operator will compare for equality after doing any necessary type conversions.
The === operator will not do the conversion, so if two values are not the same type === will simply return false.
Both are equally quick.
```
 
The user received 48 helpful responses that provided more insight than otherwise necessary, which is indeed a good thing, where other users gave further examples including diagrams that illustrated the technical nuances that lie within the original question. The ability to get help with a question whilst also helping others gain a better understanding with that same question is what lends itself to an especially smart question.

## The notorious "dumb question"

Now the next time you ask yourself, "is my question dumb?", consider this next example of a question which isn't necessarily "dumb", but more so unhelpful:

```
Q: Calculate the percentage of students who submitted homework late

I have a Table of homework submission hours from multiple schools.

The table:
--------------------------------------------------------
|Student | School | homework submission hours (timestamp)|
--------------------------------------------------------
How can I get the percentage of students that took them more than an hour to submit homework for each school?
```

Without having to look further into this user's question, just from the header alone we know that this is a homework problem, which is incredibly advised against to post on discussion forums of any kind. Judging by this user's question, there is no sign of prior research or attempts at solving the problem before posting and is reflected by the one singular response this user received to which does not seem to answer the question entirely due to its vagueness. It is questions like these that do not illicit productive discussions and obviously the intended solution for the asker. Un-smart questions will most likely be ignored, answered incorrectly or are met with contempt.

[This is the link to the question on StackOverflow.](https://stackoverflow.com/questions/66262550/calculate-the-percentage-of-students-who-submitted-homework-late)

## Conclusion

So now we know what smart and un-smart (not necessarily "dumb") questions look like. The key takeaways are to always make sure that we ask questions not solely to get an answer, but to help others whilst also getting an answer. It is always important to remember that learning takes a village, or a community, and selfishness through asking un-smart questions can do more harm than good. 
