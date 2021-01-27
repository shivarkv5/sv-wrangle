# sv-wrangle

* [input file](https://github.com/srkvodnala/sv-wrangle/blob/main/data.txt)

* [speaker 1 file](https://github.com/srkvodnala/sv-wrangle/blob/main/speaker1.txt)

* [speaker 2 file](https://github.com/srkvodnala/sv-wrangle/blob/main/speaker2.txt)

1. Assgined Play  - 16. Two Gentlemen of Verona

2. Speaker 1 - VALENTINE
3. Speaker 2 - PROTEUS

4. Who character spoke more number of times in a play?

5. Commands Used
* curl  curl "http://shakespeare.mit.edu/two_gentlemen/full.html" -O "data.txt"
* grep -c "VALENTINE" data.txt > speaker1.txt
* grep -c "PROTEUS" data.txt > speaker2.txt




