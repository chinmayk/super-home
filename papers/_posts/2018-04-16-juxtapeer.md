---
layout: paper
title: "Juxtapeer: Comparative Peer Review Yields Higher Quality Feedback and Promotes Deeper Reflection"
# logo: peerstudio.png
venue: "CHI 2018"
authors: "Julia Cambre, Scott Klemmer, Chinmay Kulkarni"
pdf: "juxtapeer.pdf"
bibtex: |
 @inproceedings{kotturi2017long,
  title={Long-Term peer reviewing effort is anti-reciprocal},
  author={Kotturi, Yasmine and Du, Andrew and Klemmer, Scott and Kulkarni, Chinmay},
  booktitle={Proceedings of the Fourth (2017) ACM Conference on Learning@ Scale},
  pages={279--282},
  year={2017},
  organization={ACM}
  }

---

## Abstract
Peer review asks novices to take on an evaluator's role, yet novices often lack the perspective to accurately assess the quality of others' work. To help learners give feedback on their peers' work through an expert lens, we present the Juxtapeer peer review system for structured comparisons. We build on theories of learning through contrasting cases, and contribute the first systematic evaluation of comparative peer review. In a controlled experiment, 476 consenting learners across four courses submitted 1,297 submissions, 4,102 reviews, and 846 self assessments. Learners assigned to compare submissions wrote reviews and self-reflections that were longer and received higher ratings from experts than those who evaluated submissions one at a time. A second study found that a ranking of submissions derived from learners' comparisons correlates well with staff ranking. These results demonstrate that comparing algorithmically-curated pairs of submissions helps learners write better feedback.

## Background
Previous peer review work had noticed that student feedback wasn't quite of the same quality as staff feedback, but most previous papers (including ours) implicitly attributed this to student motivation, how much time the task needed etc. My research group has been building peer review and feedback systems for the last five years or so, but we'd never questioned this assumption. 

Julia did. She correctly points out in this paper that poor peer feedback isn't just about motivation -- students simply don't know what teachers know. How can we expect them to write teacher-like feedback? To do so, we must first help students see what teachers see. Her system Juxtapeer does this by using contrasting cases. Read the paper for details.


## Frequently asked questions
**Q: You ask students to compare two submissions at a time. Will comparing more (say three) help?**

**A** Probably not. Contrasting cases rely on alignment of structural features. This alignment task is easiest if you only have two artifacts. 

**Q: What domains does this work for? Will it work with math?**

**A** Maybe, but unlikely. Contrasting cases, and constructivist learning more generally, are best suited to open-ended solutions. If there is only one right answer, and not varying degrees of goodness, juxtaposing different examples will likely have little value. 

**Q: Why is it called Juxtapeer?**

**A** Because "juxtapose" and "peer". It's not just a clever name; juxtaposition is really important. Prior research has shown that people don't spontaneously make comparisons unless they are specifically asked to do so, and the artifacts are visually alignable. 

**Q: What other counter-intuitive things should I think about with peer review?**

**A** Read Angela Duckworth's paper on the benefits of [giving vs. receiving feedback.](https://journals.sagepub.com/doi/abs/10.1177/0956797618795472) I continue to be amazed at how people ask ``What's in it for me?'' when the research shows that the benefits of giving advice are so much larger than receiving advice. 