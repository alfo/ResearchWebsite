# Program Verification

## About
Program verification is defined as 'the study of mathematical methods for verifying whether or not a program executes as it is intended'. This means applying mathematics to test if a program runs correctly. 

The goal of program verification is to prevent unintended consequences, caused by errors in the code, when running a program. This is especially important in mission-critical systems (where the computer is essential in performing a task, such as one on board a space shuttle). Ultimately, good program verification prevents loss of assets, reputation and sometimes lives. 

## Why Verification Matters
Nowadays, cockpits do not have many mechanical controls for piloting the aircraft. Instead, they have computers embedded in the aircraft and these computers control all the engine operations, hydraulic operations, etc. to make the aircraft fly. In this case, if an error occurs at runtime within the program installed on an aircraft computer, it can suddenly switch off all the engines and will not process any commands that pilots make to control flaps, rudders, or elevators as well as the engines. Such a failure could cost the lives of hundreds of passengers.

Additionally, even if a visible runtime error didn't occur, a calculation error could have catastrophic impacts. For instance, if the flight management computer fails to show the accurate flight path, then the aircraft could fly through restricted zones, putting the aircraft at risk of triggering military defences. Good program verification reduces the chances of such events occurring.

For the space industry, it is also important to ensure that the software runs as intended since the cost of launching a spacecraft is tremendous. 
<video:http://www.youtube.com/watch?v=kYUrqdUyEpI>
This video shows an infamous example of an unverified program causing an accident, namely the launch of the “Ariane 5” rocket.This explosion was caused by the imprecision when converting between two different data types, floating point values (such as 1.234) and integers. This imprecision caused an exception, meaning that the program could not run as expected. Thus the rocket control system failed, and the rocket itself exploded.

## History of program verification
### Timeline from [2]
1947 - John Von Neumann <img: verification_9> -He suggested that for ensuring the correctness of the program, writing assertions in a flow diagram is crucial.

1949 - Alan Turing <img: verification_10> - He summarised a very important mathematical thought that is required for program verification in his paper 'Checking a Large Routine'. <img:verification_12>

1953 - Henry Rice - He suggested that no mechanical device can verify the correctness of a program.

1955 - John McCarthy - He realised the importance of mathematical logic in program verification and drew attention to the field of program verification.

1955 - Alfred Talski <img: verification_11> - His research resulted in a theorem called the 'Fixed point theorem', which is key to the field.

1967 - Robert Floyd <img: verification_13> - Inspired by John McCarthy, he summarised how program verification can be done. His paper, 'Assigning Meaning to Programs', <img:verification_14>, is cited today as the origin of program verification.

1977 - Edmund Clarke <img: verification_15> -Showed that the process of program reasoning could be viewed as a calculation in his paper 'Program Invariants As Fixed Points'<img:verification_16>.
 
2009 - Joseph Sifakis et al. - They suggested a way to overcome the limitations of program verification, as outlined by Rice's Theorem.
 
## Key People
1. Dr. James Brotherston
<img: verification_6>
   - Reader in Logic and computation
   - Programming principles, logic and verification research group
   - Email: j.brotherston@ucl.ac.uk  
   - Description: Dr. Brotherston specialises in looking at logic in program verification.
2. Prof. Brad Karp
<img: verification_7>
   - Professor of Computer Systems and Networks.
   - Head of systems and networks research group.
   - Email: b.karp@cs.ucl.ac.uk
   - Description: Prof. Brad Karp specialises in computer systems and networks, and makes contributions to verification research.
   
3. Dr Jade Alglave
<img: verification_8>
   -  Reader in computer system
   -  Intelligent systems research group
   -  Email: j.alglave@cs.ucl.ac.uk
   -  Description: As shown by her publications, Dr. Jade Alglave has broad range of research interests. She is currently contributing to verification research.




# Bibliography
[2] V. D’Silva, Tales from verification history, 2009,[online access] http://www.cs.ox.ac.uk/publications/publication3240-abstract.html/  [Accessed on 16/10/2017]
