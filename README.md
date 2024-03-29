# Software Development Reading List

This reading list contains links to texts about software development.

Texts are roughly organized by topic and annotated with a tag, indicating the kind of text. A two to three sentence summary gives a general idea about each texts content. Summaries are omitted if the texts title is clear enough. 

### Topics
- [Complexity](#complexity)
- [Software Architecture](#software-architecture)
    - [Fundamentals](#fundamentals)
    - [Software Design](#software-design)
    - [Lean Software](#lean-software)
    - [Technical debt](#technical-debt)
    - [Communicating architecture to business](#communicating-architecture-to-business)
- [Requirements](#requirements)
- [Development process](#development-process)
- [Networks](#networks)
- [Legacy systems](#legacy-systems)
- [Artificial Intelligence](#artificial-intelligence)
    - [Safety of AI](#safety-of-ai)
    - [Code generation - Coding with AI](#code-generation--coding-with-ai)
    - [Large Language Models](#llms---large-language-models)
- [Trivia](#trivia)
    - [Bugs](#bugs)

### Tags
**[P]** Scientific Paper\
**[A]** Article\
**[AS]** Article-Series\
**[BA]** Blog Article\
**[E]** Essay\
**[B]** Book\
**[G]** Guide

**[Classic]** A text with significant influence on the field.

### How to participate
Raise an Issue on GitHub to comment on this list.\
Text suggestions are welcome, as are error reports.

---

# Complexity

> Increasingly, people seem to misinterpret complexity as sophistication, which is baffling — the incomprehensible should cause suspicion rather than admiration. - Niklaus Wirth

**[P][Classic] No Silver Bullet (1986)**\
Distinguishing between accidental and essential complexity. Identification of essential complexity as inherent to most software problems. Arguing for limited possibilities to improve on tackling this essential complexity.\
http://worrydream.com/refs/Brooks-NoSilverBullet.pdf

**[P][Classic] Out of the Tar Pit (2006)**\
Complexity as the single major source of difficulty in the development of large software systems. Causes of complexity and how to avoid accidental complexity.\
https://curtclifton.net/papers/MoseleyMarks06a.pdf

# Software Architecture

## Fundamentals

**[P][Classic] On the criteria to be used in decomposing systems into modules (1972)**\
Proposing to decompose systems by identifying (possibly changing) design decisions and grouping modules so that changes effect only one module. Arguing for 'information hiding' and well defined interfaces. Aiming for improved changeability, independence of modules and comprehensibility.\
https://dl.acm.org/doi/10.1145/361598.361623

**[P][Classic] Information distribution aspects of design methodology (1972)**\
Introducing information hiding and encapsulation, to increase the decoupling of modules.\
https://cseweb.ucsd.edu/~wgg/CSE218/Parnas-IFIP71-information-distribution.PDF

**[B] Clean Architecture: A Craftsman's Guide to Software Structure and Design**\
Describes general principles of software architecture on a fairly abstract level.\
(no link, easily found by any search engine)

**[B] Fundamentals of Software Architecture: An Engineering Approach.**\
Introduction and overview of software architecture’s many aspects. Topics include architectural characteristics and patterns, component determination and a overview of common architectures.\
 https://www.oreilly.com/library/view/fundamentals-of-software/9781663728357/

**[AS] Continuous Architecture**\
Series of articles exploring software architecture as decisions on how systems should handle non-functional requirements.\
https://www.infoq.com/articles/continous-architecture-article-series/

**[A] Agility and Architecture: Balancing Minimum Viable Product and Minimum Viable Architecture**\
Discussing the role of software architecture in agile development. Focus on the timing of architectural decisions.\
https://www.infoq.com/articles/agility-architecture

**[P] The Accidental Architecture**\
Main point: Accidental architectures emerge but then become intentional only after they’ve proven themselves through time.\
https://www.inf.ed.ac.uk/teaching/courses/seoc/2006_2007/resources/Arc_Accidental.pdf

## Software Design
**[B] Clean Code**\
Proposes and discusses a wide array of coding principles which lead to readable, changeable, maintainable code. Demonstrates these principles in lots of code examples.

**[A] Avoiding repetition**\
Arguments for removing duplicate code. Benefits and challenges when doing so.\
https://martinfowler.com/ieeeSoftware/repetition.pdf

**[BA] BeckDesignRules**\
Short summary of Kent Beck's four rules of good software design.\
https://martinfowler.com/bliki/BeckDesignRules.html

## Lean Software
**[A] Why Bloat Is Still Software’s Biggest Vulnerability. A 2024 plea for lean software**\
Arguing for less reliance on unchecked third party dependencies. Strong plea for writing small, comprehensible software.\
https://spectrum.ieee.org/lean-software-development

**[BA] Is software getting worse?**\
Exploring how current market trends lead to decreasing software quality.\
https://stackoverflow.blog/2023/12/25/is-software-getting-worse

## Technical debt
**[A] What Does Technical Debt Tell You?**\
Introduction to the technical debt metaphor. Difficulties in quantifying technical debt. Shortcomings of the metaphor.\
https://www.infoq.com/articles/technical-debt-tells-you

**[A] Technical Debt is Quantifiable as Financial Debt: an Impossible Thing for Developers**\
Difficulties in converting measures of technical debt to financial debt, as in financial effort needed to fix the technical debt.\
https://www.infoq.com/news/2022/09/financial-debt-impossible

**[A] Using the Technical Debt Metaphor to Communicate Code Quality**
Exploring the metaphor. Emphasizing not managed technical debt as the main problem.\
https://www.infoq.com/news/2022/10/technical-debt-code-quality

## Communicating architecture to business

**[A] How to Have More Effective Conversations with Business Stakeholders About Software Architecture**\
https://www.infoq.com/articles/effective-architecture-conversations


# Requirements

**[G] A practical guide to writing technical specs**\
What a technical spec is. Why and how to write one.\
https://stackoverflow.blog/2020/04/06/a-practical-guide-to-writing-technical-specs

**[A] Requirements volatility is the core problem of software engineering**\
https://stackoverflow.blog/2020/02/20/requirements-volatility-is-the-core-problem-of-software-engineering

**[A] The hardest part of building software is not coding, it's requirements**\
Unclear requirements as a challenge and as the reason why code generating AI will not be able to replace software engineers.\
https://stackoverflow.blog/2023/06/26/the-hardest-part-of-building-software-is-not-coding-its-requirements

# Development process

**[A] Does scrum ruin great engineers or are you doing it wrong?**\
Summary of a discussion about scrum on the software engineering stackexchange. List of common problems in implementing scrum.\
https://stackoverflow.blog/2020/06/29/does-scrum-ruin-great-engineers-or-are-you-doing-it-wrong

**[A] Can developer productivity be measured?**\
Discussion of several, often used measures of dev productivity and their potential problems.\
https://stackoverflow.blog/2020/12/07/measuring-developer-productivity

**[BA] CannotMeasureProductivity**\
Arguments that measuring developer productivity is futile.\
https://martinfowler.com/bliki/CannotMeasureProductivity.html

# Networks
**[B] Where wizards stay up late: The Origins Of The Internet**\
Focus on the people involved. Good story, but little to no technical details.\
https://books.google.de/books/about/Where_Wizards_Stay_Up_Late.html

# Legacy systems

**[AS] Patterns of Legacy Displacement**\
Challenges and best practices of replacing legacy systems.\
https://martinfowler.com/articles/patterns-legacy-displacement

# Artificial Intelligence

## Safety of AI
**[P] Concrete Problems in AI Safety**\
Discussion of 5 concrete problems for AI safety, in three categories: Wrong objective function ("avoiding side effects" and "avoiding reward hacking"), objective function  is too expensive to evaluate frequently ("scalable supervision"), and undesirable behavior during the learning process ("safe exploration" and "distributional shift").\
https://arxiv.org/abs/1606.06565 

## Code generation / coding with AI

**[BA] Is AI enough to increase your productivity?**\
Possibilities and limits of increasing coding productivity with the use of AI tools.\
https://stackoverflow.blog/2023/10/16/is-ai-enough-to-increase-your-productivity

## LLMs - Large Language Models

**[BA] Privacy in the age of generative AI**\
Describes data privacy problems in training and usage of LLM's and proposes the use of a data privacy vault as a solution.\
https://stackoverflow.blog/2023/10/23/privacy-in-the-age-of-generative-ai

# Trivia

## Bugs

**[BA] The most copied StackOverflow snippet of all time is flawed!**\
Nice bug in printing a byte count in a human readable format.\
https://programming.guide/worlds-most-copied-so-snippet.html