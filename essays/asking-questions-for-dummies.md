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

```
A: The strict equality operator (===) behaves identically to the abstract equality operator (==)
except no type conversion is done, and the types must be the same to be considered equal.

The == operator will compare for equality after doing any necessary type conversions.
The === operator will not do the conversion, so if two values are not the same type === will simply return false.
Both are equally quick.
```
 
The user received 48 helpful responses that provided more insight than otherwise necessary, which is indeed a good thing, where other users gave further examples including diagrams that illustrated the technical nuances that lie within the original question. The ability to get help with a question whilst also helping others gain a better understanding with that same question is what lends itself to a smart question.

## The notorious "dumb question"

While there are decent questions that benefit everyone, there are those one can ask to create an entirely different effect. In the following example, a user asks how he would, in short, create a desktop application with Facebook.

```
Q: Facebook Desktop Notifier

I am a beginner programmer that have never used anything other than what's included in a language.

I am trying to create a desktop application that notifies me anytime I get an update onfacebook. 
How should go about doing this? Thanks in advance.

edit Sorry I was not clear. Is there any way to make a DESKTOP application with facebook?
```

A simple “yes” would have answered the question, but we know that’s not the sort of answer he or she is looking for. Fortunately, someone kindly responded with a link to Facebook’s developer website. The asker should have done more research on his or her potential project. Then further down the road, he or she could have asked more specific and detailed questions that wouldn’t require a thousand-paged response for a sufficient answer.

## Conclusion

When we rely on others’ generosity and expertise to provide answers to our questions, it should hold that the question we ask should be one that leads to efficient and effective help that not only benefits us, but also the people we ask and others who might ask the same question in the future. Thus, if you have a question… make it a smart one! Asking questions may not always get you the best answer, but asking them in a way that will make others want to answer them will increase the success of finding a good solution and make it a positive experience on all sides.
