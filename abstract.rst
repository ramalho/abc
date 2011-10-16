If Guido is the father of Python, then ABC is the mother. ABC was a programming language and environment designed by Leo Geurts, Lambert Meertens and Steven Pemberton and CWI in the Netherlands during the 1980's. Guido van Rossum was a member of the ABC team and went on to design Python to be "almost, but not quite, entirely unlike ABC" [1](http://www.computerworld.com.au/article/255835/-z_programming_languages_python "Guido interview to Computerworld, Aug. 2008").

About ABC
=========

Steve Pemberton's definition is the best I've found: 

> A simple but powerful interactive programming language and environment. We did requirements and task analysis, iterative design, and user testing. You'd almost think programming languages were an interface between people and computers. Now famous because Python was strongly influenced by it. [2](http://homepages.cwi.nl/~steven/#pls "Steve Pemberton's homepage at CWI")

Why ABC is relevant today
=========================

Guido departed from ABC to create a much more practical, all-purpose language. But today Python is increasingly being used also as a first programming language in schools and universities. This use as an educational tool and as a language for casual programmers can be informed by the choices made by the original ABC team, as revealed by the language implementation, it's environment, and several publications about it.

About this talk
===============

The aim is to answer the question: "What can current and future Python IDEs and libraries aimed at beginning or casual programmers learn from ABC, a language and environment explicitly designed for that audience?"

The similarities and differences between Python and ABC will be shown, often with side-by-side code comparisons. Among the similarities, we will cover:

 * *foreach* style `for` command, with tuple unpacking
 
 * extensive use of dicts and tuples (called "tables" and "compounds")
 
 * unbounded integers and strings
 
 * block structure by indentation
 
ABC also had some features that Python did not inherit:

 * lists were only allowed to contain items of the same type, and were automatically kept sorted
 
 * variables could only be bound to a single type during one function invocation
 
 * files were not supported: instead, the environment auto-saved objects like functions and global variables in workspaces (similar to Smalltalk images) for use in future sessions; also, a table-like global variable could be bound to an external text file for I/O, but this binding could not be changed within a session 
 
ABC also included an editor and interactive console with auto-completion, auto-indentation and other aids. It used the concept of workspaces which allowed modular programming without explicit handling of packages and imports.

The merits of these and some other features that Python dropped or changed will be discussed in the context of Python usage in schools. For instance, although implicit and constrained file I/O may be shocking to professional programmers, there are similar features in programming systems designed for non-programmers, such as Hypercard and more recently, Processing. 
 
### Additional notes

I've been a Python evangelist and instructor since 1998, but have taught programming to beginners and new languages to professional developers before that, and I have also developed educational software, so the interaction between programming and learning is a lifelong inteterst of mine. Recently I've run "programming workshops for everyone" using Processing and Python at cultural centers in Brazil. I hold the record for all-time replies in the python-brasil mailing list, with 1727 posts as of today, mostly helping newcomers to the language, and I have written a popular Python tutorial for non-programmers, in Portuguese.


 


