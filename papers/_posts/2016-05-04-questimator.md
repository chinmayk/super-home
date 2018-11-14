---
layout: paper
title: "Questimator: generating knowledge assessments for arbitrary topics"
logo: peerstudio.png
venue: "AAAI 2016"
authors: "Qi Guo, Chinmay Kulkarni, Aniket Kittur, Jeffrey P Bigham, Emma Brunskill"
pdf: "questimator_msthesis.pdf"
bibtex: |
  @inproceedings{guo2016questimator,
  title={Questimator: generating knowledge assessments for arbitrary topics},
  author={Guo, Qi and Kulkarni, Chinmay and Kittur, Aniket and Bigham, Jeffrey P and Brunskill, Emma},
  booktitle={Proceedings of the Twenty-Fifth International Joint Conference on Artificial Intelligence},
  pages={3726--3732},
  year={2016},
  organization={AAAI Press}
  }

---
### Background
Qi Guo was a masters students advised by Emma Brunskill. Questimator was his masters dissertation. While it was published in IJCAI, I'm linking Qi's masters thesis, which has a little bit more detail, in the hopes that it will help others see details of the implementation. 


### Abstract
Formative assessments allow learners to quickly identify knowledge gaps. In traditional educational settings, expert instructors can create assessments, but in informal learning environments, it is difficult for novice learners to self assess because they don’t know what they don’t know. This paper introduces Questimator, an automated system that generates multiple-choice assessment questions for any topic contained within Wikipedia. Given a topic, Questimator traverses the Wikipedia graph to find and rank related topics, and uses article text to form questions, answers and distractor options. In a study with 833 participants from Mechanical Turk, we found that participants’ scores on Questimator-generated quizzes correlated well with their scores on existing online quizzes on topics ranging from philosophy to economics. Also Questimator generates questions with comparable discriminatory power as existing online quizzes. Our results suggest Questimator may be useful for assessing learning in topics for which there is no existing quiz.
