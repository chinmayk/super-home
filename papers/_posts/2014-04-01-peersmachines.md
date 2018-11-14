---
layout: post
title: "Scaling Short-answer Grading by Combining Peer Assessment with Algorithmic Scoring"
venue: "Learning@ Scale 2014"
authors: "Chinmay Kulkarni, Richard Socher, Michael S Bernstein, Scott R Klemmer"
pdf: "StickyPeerLearningLAS2015.pdf"
bibtex: |
  @inproceedings{Kulkarni:2014humanMachine,
   author = {Kulkarni, Chinmay E. and Socher, Richard and Bernstein, Michael S. and Klemmer, Scott R.},
   title = {Scaling Short-answer Grading by Combining Peer Assessment with Algorithmic Scoring},
   booktitle = {Proceedings of the First ACM Conference on Learning @ Scale Conference},
   series = {L@S '14},
   year = {2014},
   isbn = {978-1-4503-2669-8},
   location = {Atlanta, Georgia, USA},
   pages = {99--108},
   numpages = {10},
   url = {http://doi.acm.org/10.1145/2556325.2566238},
   doi = {10.1145/2556325.2566238},
   acmid = {2566238},
   publisher = {ACM},
   address = {New York, NY, USA},
   keywords = {assessment, automated assessment, online learning, peer learning},
  }


---

**Abstract**  Peer assessment helps students reflect and exposes them to different ideas. It scales assessment and allows large online classes to use open-ended assignments. However, it requires students to spend significant time grading. How can we lower this grading burden while maintaining quality? This paper integrates peer and machine grading to preserve the robustness of peer assessment and lower grading burden. In the identify-verify pattern, a grading algorithm first predicts a student grade and estimates confidence, which is used to estimate the number of peer raters required. Peers then identify key features of the answer using a rubric. Finally, other peers verify whether these feature labels were accurately applied. This pattern adjusts the number of peers that evaluate an answer based on algorithmic confidence and peer agreement. We evaluated this pattern with 1370 students in a large, online design class. With only 54% of the student grading time, the identify-verify pattern yields 80-90% of the accuracy obtained by taking the median of three peer scores, and provides more detailed feedback. A second experiment found that verification dramatically improves accuracy with more raters, with a 20% gain over the peer-median with four raters. However, verification also leads to lower initial trust in the grading system. The identify-verify pattern provides an example of how peer work and machine learning can combine to improve the learning experience.
