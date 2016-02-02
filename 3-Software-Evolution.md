# Topic 3 - Software Evolution

Starting Monday Feb 1st

## Suggested Reading

First of all, read David Parnas’ classic paper on Software Aging: http://www.inf.ed.ac.uk/teaching/ courses/seoc/2004_2005/resources/bullet11.pdf

In light of this, have a look at this more recent case study from SoundCloud, migrating from a monolithic application to small services. http://philcalcado.com/2015/09/08/how_we_ended_up_with_microservices.html

Also relevant is Adam Tornhill's work on "[Code as a Crime Scene](http://www.adamtornhill.com/articles/crimescene/codeascrimescene.htm)" and his tool [Code-Maat](https://github.com/adamtornhill/code-maat).

Here’s an article by Jonny Arnold from Revoo that gives some examples of things that he did with Code-Maat on their code base http://reevoo.github.io/blog/2015/05/21/your-code-as-a-crime-scene/


Think about the following questions:

- Which do you think is more useful in understanding a codebase, its history or its current state? 
- Do you think radical changes in structure show a failing in initial design?
- Can you tell from the version control history whether a system is well architected?