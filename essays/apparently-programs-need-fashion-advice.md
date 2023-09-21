---
layout: essay
type: essay
title: "Apparently Programs Need Fashion Advice"
# All dates must be YYYY-MM-DD format!
date: 2023-09-21
published: true
labels:
  - Quality Assurance
  - Coding Standards
  - Programming Style Guide
---

<img width="500px" class="rounded float-start pe-4" src="https://www.fatosmorina.com/wp-content/uploads/2017/04/coding-style.jpg">

## The dilemma

Have you ever once looked at someone else's code and thought to yourself, "why do they code like that?". This is a common sentiment shared by myself and many other programmers who have had the misfortune of reviewing code written by others, where in various instances misplaced curly brackets and indentations are only a sliver of the issues that give rise to our frustration. Ideally, in a perfect world, everyone would program the exact same way regardless of the language, but alas, that is far from reality. Just as no two people will write the same essay using the same exact handwriting, the same can be said when coding a program, but in this context, the same coding conventions. That is, without the use of coding standards.

## A "one size fits all" tool

As an emerging programmer, I have had some exposure to coding standards, one being in the form of Checkstyle, which is the premier code analysis tool used for ensuring that Java source code is compliant with specified coding rules. The utilization of Checkstyle was heavily required back when I was learning the Java programming language, and quite frankly, I can now see why that was so in hindsight. Although my first object-oriented programming language, Java was one of the more obscure languages in my opinion when it came to collaborating on projects with other programmers, especially when those projects included numerous classes and utilized inheritance. Checkstyle in particular put significant emphasis on commenting style in terms of method declarations and ensured that we specified the definitions for each parameter and return value. Inevitably, this allowed me to become a better programmer as it instilled in me the importance of program readability, especially when collaborating with others. 

## More so uniform, less on the fashion

In my humble opinion, I believe that curly brackets are more readable if they are placed on a new line, but that may just be me. Personally, coding this way allows me to perceive blocks of code as actual *blocks of code* while the more common curly bracket placement on the same line, to me, makes the code more convoluted and chaotic to read as more nested control structures are used. Again, this is all just personal preference, and partially my distate for the curly bracket style that ESLint enforces. Though, besides the point, coding standards regardless of the specific style they require can only make collaborating in the programming world more streamlined and accessible. Believe it or not but the majority of open source code is compliant with their respective coding standards, and speaking from personal experience, having online programming resources written and formatted in one singular, standardized way has made learning much more enjoyable. If programmers coded in their own specific style, I fear there would be much more confusion than anything and learning would not be as enjoyable. Although I may have my grievances with the specific coding style that ESLint implements, getting that green check mark has never been more satisfying.

## Walking the runway

Just as fashion advice can help individuals present themselves more effectively, coding standards help programmers present their code in a way that is universally understandable. They provide a common ground where diverse talents can converge, making it easier for developers to work together, learn from one another, and contribute to the ever-evolving world of technology.

So, while we may continue to have spirited debates about the placement of curly brackets or the use of specific coding conventions, we should appreciate the broader goal that coding standards aim to achieve—making code more readable, maintainable, and accessible to everyone. In the end, it's not about enforcing uniformity but fostering a shared understanding that helps us communicate through code and build a more collaborative and innovative programming community. As we navigate the world of programming, let's remember that in our code's fashion choices, a touch of standardization can go a long way.