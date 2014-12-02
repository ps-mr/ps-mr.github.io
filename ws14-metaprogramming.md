---
layout: index
---

# Metaprogramming Seminar

Metaprograms process and produce source code. A metaprogram treats a regular program as data and thus enables abstractions and reflections outside the scope of regular programming languages. Metaprogramming is widely applied in programming languages. From C++ templates and syntactic macros, to model-driven development, domain-specific languages and aspect-oriented programming: Metaprogramming plays a significant role in many modern programming systems. In this seminar, we study the foundations of metaprogramming and its applications in modern software development by reading research papers on the topic.

More details will be announced through this page.

### Instructors

Paolo G. Giarrusso (Office: Room B211)\\
Prof. Klaus Ostermann

### Seminar schedule

Each week, please prepare and submit a summary and questions by the *Monday, 23:59* before the meeting.

1. Tuesday 28.10.\\
On *programs as data*: McCarthy, 1960.
[Recursive functions of symbolic expressions and their computation by machine, part 1](http://cs.cmu.edu/~crary/819-f09/McCarthy60.pdf), *Communications of the ACM*.
The original version is [here](http://www.brinckerhoff.org/clements/csc530-sp09/Readings/mccarthy-1960.pdf).\\
*[Bibliographic data/official version](http://dl.acm.org/citation.cfm?id=367199)*.\\
Feel free to skip Sec. 5.

    Discussion leader: Paolo.

2. Tuesday 4.11.\\
On *macros*: Weise and Crew, 1993.
Programmable Syntax Macros, *Proceedings of PLDI*.\\
*[Bibliographic data/official version](http://dl.acm.org/citation.cfm?id=155105)*.

    Discussion leader: Werner.

3. Tuesday 11.11.\\
On *syntax macros* and *sugar libraries*: Erdweg, Rendel, Kästner, and Ostermann, 2011.
[SugarJ: Library-based syntactic language extensibility](http://www.student.informatik.tu-darmstadt.de/~xx00seba/publications/sugarj.pdf), *Proceedings of OOPSLA*.\\
*[Bibliographic data/official version](http://dl.acm.org/citation.cfm?id=2048099)*.

    Discussion leader: Julian.

4. Tuesday 18.11.\\
On *staging*: Walid Taha and Tim Sheard, 1997.
[Multi-stage programming with explicit annotations](http://pdf.aminer.org/000/538/255/multi_stage_programming_with_explicit_annotations.pdf), *Proceedings of PEPM*.\\
*[Bibliographic data/official version](http://dl.acm.org/citation.cfm?id=259019)*.

    Please focus on Sec. 1-10 and 13, but take a look at the rest.\\
Discussion leader: Kristina.

5. Tuesday 25.11.\\
On *Template Haskell*: Tim Sheard and Simon Peyton Jones, 2002.
[Template meta-programming for Haskell](http://research.microsoft.com/en-us/um/people/simonpj/Papers/meta-haskell/meta-haskell.pdf), *Proceedings of Haskell Workshop*.\\
*[Bibliographic data/official version](http://dl.acm.org/citation.cfm?doid=581690.581691)*.

    Discussion leader: Jonas.

    Focus on the high-level picture (as discussed by the guides to reading
    papers), not so much on the details of the Haskell API. My suggestion is to
    please focus on Sec. 1-5, 10 and 12, skim Sec. 6, 7, 8.1, 9, but skip Sec.
    9.3.

    See also, for background on the notation of Fig. 2 (in Sec. 7),
    [this note by Prof. Jeremy Siek](http://siek.blogspot.de/2012/07/crash-course-on-notation-in-programming.html). Understanding code snippets is not so critical, but [some cheatsheets exist](http://fundeps.com/posts/cheatsheets/2014-03-04-cheat-sheets/), though I'm not sure which to recommend.

6. Tuesday 2.12.\\
On *domain-specific languages and deep embedding*:
Conal Elliott, Sigbjørn Finne and Oege De Moor, 2003. Compiling embedded languages, *Journal of Functional Programming*.\\
*[Bibliographic data/official version](http://journals.cambridge.org/article_S0956796802004574)*.

    Discussion leader: Jan.

7. Tuesday 9.12.

8. Tuesday 16.12.
\\
\\
**Christmas break**

9. Tuesday 13.01.

10. Tuesday 20.01.

11. Tuesday 27.01.

12. Tuesday 3.02.

13. Tuesday 10.02.

### Other relevant papers (to pick from for future meetings)

* On *staging* and *language virtualization*: Rompf and Odersky, 2012. [Lightweight modular staging: a pragmatic approach to runtime code generation and compiled DSLs](http://dl.acm.org/citation.cfm?id=2184345).

* On *macros and hygiene*: Clinger and Rees, 1991. [Macros that work](http://dl.acm.org/citation.cfm?id=99607).

* On *metaobject protocols*: Kiczales, Ashley, Rodriguez, Vahdat, and Bobrow, 1993. [Metaobject protocols: why we want them and what else they can do](http://cseweb.ucsd.edu/~vahdat/papers/mop.pdf).

Further papers will be listed, depending on topics of interest.

### Other info
Language: English\\
Credits: 4 LP\\
[LSF entry](http://campus.verwaltung.uni-tuebingen.de/lsfpublic/rds?state=verpublish&status=init&vmfile=no&publishid=114223&moduleCall=webInfo&publishConfFile=webInfo&publishSubDir=veranstaltung)\\
Weekly meeting: Tuesday, 18:15-19:45 --- room [C311](http://campus.verwaltung.uni-tuebingen.de/lsfpublic/rds?state=verpublish&status=init&vmfile=no&moduleCall=webInfo&publishConfFile=webInfoRaum&publishSubDir=raum&keep=y&raum.rgid=2963)\\
Contact email: paolo (dot) giarrusso (at) uni-tuebingen (dot) de

### Kick-off meeting

21.10.2014 17:15-19:00, [Room A302](http://campus.verwaltung.uni-tuebingen.de/lsfpublic/rds?state=verpublish&status=init&vmfile=no&moduleCall=webInfo&publishConfFile=webInfoRaum&publishSubDir=raum&keep=y&raum.rgid=2786).\\
[Introduction slides](https://github.com/Blaisorblade/ws14-mp/blob/master/WS14-Metaprogramming.pdf?raw=true).

### Course structure

During the semester, we will discuss together a paper each week in a meeting. Everybody should read the paper in advance, prepare and submit a short summary and questions (150-300 words). A discussion leader should dig deeper on the topic, also based on the questions by other students, and prepare to moderate the discussion. The role of discussion leader rotates among students.

At the end of the semester, each participant should submit a short term paper, surveying one of the discussed topics.

The seminar is graded, and the final grade depends on both the summaries, the participation to the discussion, and the final term paper.

### Tips on reading papers

There are different approaches to reading a research paper, some more productive than others. While there are no strict rules, you might want to take a look at the following:

* Philip W. L. Fong, 2004. [How to Read a CS Research Paper?](http://faculty.ksu.edu.sa/chikh/Documents/reading-paper.pdf) (4 pages).
* S. Keshav, 2007. [How to Read a Paper](http://groups.csail.mit.edu/netmit/wordpress/wp-content/themes/netmit/papers/HowtoRead.pdf) (2 pages).

### Absence policy

This seminar is a discussion seminar, so it is necessary that you actually attend meetings in order to benefit from the seminar and pass the exam.

You are allowed to miss at most two of the meetings and still pass the seminar. Should this become a problem and should the absences be due to justifiable reasons, we *might* be able to agree on alternative loads to compensate for the absences.
