# SpontaneousAlternations

Automated analysis for a *Spontaneous Alternations Task* for mice. This script includes data post processing and individual/group analysis.


**Spontaneous Alternation Task**

Behavioral experiment to test short-term memory which takes advantage of the innate exploratory behavior of mice. In short, we use a three-arm Y-maze and record the entries and alternations to the different arms. The arms would be labelled A-B-C.

Entries: All 4 limbs of a mouse are within an arm;
Alternations: Consecutive entries into all three arms (Figure below);

<img src="https://os.bio-protocol.org/attached/image/20190130/20190130014520_2422.jpg" width="500">

To calculate the alternations percentage, we should use the following formula:

*%alternations* = 100 x (nº of alterations / total nº of arm entries)

A high *%alternations* should indicate a good short-term memory while a low *%alternations* suggests a poor short-term memory.
