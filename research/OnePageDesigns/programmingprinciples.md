# Programming Principles

## About
Programming Principles is a subset of the larger area of Theoretical Computer Science. Programming Principles include fundamental concepts such as use of resources, language design and how programmers think. 

Computer Science is still a very young field. Therefore, it is highly likely that our current understanding of systems, programs and resources still needs refining. The value of creating these new approaches to programming is that, ideally, they will result in safer, faster and more reliable computing.

## Why Principles Matter (Working Title)
The reason that programming principles such as DRY (Don't Repeat Yourself) and YAGNI (You Aren't Gonna Need It) exist are to aid programmers in designing their software well. Important criteria for well-designed software include the software being testable, clear and well-documented. Poorly-designed software is difficult to fix, if the issues can even be diagnosed at all.

Bad software design can lead to devastating consequences, as tragically seen in the 1980s. The Therac-25 was a pioneering radiation therapy machine, produced in 1982 in Canada, that was supposed to treat patients with cancer. However, due to numerous issues in the code, the machine occasionally malfunctioned and administered radiation doses hundreds of times greater than the intended dose. There were at least six accidents of this nature, between 1985 and 1987, resulting in three deaths. 

<img: therac_25>

When the code was scrutinised, researchers found that a deadly cocktail of problems caused this tragedy. One issue was that code was reused from older models of the hardware, and said code didn't function properly in the new machine. Another was that even though the system detected an error with the dosage, it only displayed a simple error code which was even mentioned in the user manual. Thus the operators, who had become so accustomed to seeing 'MALFUNCTION' display on the screen for relatively trivial errors, ignored the important warnings and allowed the machine to continue running. Thus, the importance of well-designed, well-documented and well-tested code must never be underestimated.

## History of Programming Principles
1954 - FORTRAN is developed at IBM. It was the first general purpose programming language used in machines.

1982 - One of the first mentions of the abstraction principle, in a book by A. J. Cole and R. Morrison [2]. The abstraction principle involves creating a function to use multiple times in a program instead of simply copy-pasting the same code throughout.

1999 - Kent Beck publishes 'Extreme Programming Explained', which consolidated many important programming principles and took them to extreme levels.

2001 -'Manifesto for Agile Software Development' is published. Agile software development places emphasis on flexibility and continuous iteration.

## Key People
1. Prof. Peter O'Hearn
<img: Peter>
   - Professor of Computer Science
   - Programming Principles, Logic and Verification Group
   - Email: p.ohearn@cs.ucl.ac.uk
   - Description: Prof. O'Hearn has researched broad, abstract topics, including programming languages. He is currently working at Facebook.

2. Prof. Byron Cook
<img:  Byron>
   - Professor of Computer Science
   - Programming Principles, Logic and Verification Group
   - Email: b.cook@cs.ucl.ac.uk
   - Description: Prof. Cook has performed research in areas that include programming languages and theorem proving. He is also a Director at Amazon Web Services.

3. Prof. David Pym
<img: David>
   - Professor of Information, Logic and Security
   - Head of the Programming Principles, Logic and Verification Group
   - Email: d.pym@cs.ucl.ac.uk
   - Description: Prof. Pym, who specialises in logic, uses logic-based methods to develop new methods of reasoning about systems and behaviour.












## Bibliography
1. Leveson N. Medical Devices: The Therac-25. Available from: http://sunnyday.mit.edu/papers/therac.pdf
2. Cole AJ, Morrison R. An introduction to programming with S-algol. CUP Archive; 1982, ISBN 0-521-25001-3, 150 p.
Jump up ^