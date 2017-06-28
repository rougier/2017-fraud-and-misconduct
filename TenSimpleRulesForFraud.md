# Ten Simple Rules for Scientific Fraud & Misconduct
**Nicolas P. Rougier** ∙ INRIA Bordeaux Sud-Ouest Talence, France ∙ Institut des
Maladies Neurodégénératives, Université de Bordeaux, CNRS UMR 5293, Bordeaux,
France ∙ LaBRI, Université de Bordeaux, Institut Polytechnique de Bordeaux, CNRS
UMR 5800, Talence, France


## Introduction

So, here we are! You've decided to join the dark side of Science. That's great! You'll soon discover a brand new world of shiny and surprising results, non-replicable experiments, fabricated data, funny statistics, fame and shame, joy and sadness, and... jail. But you've made your choice (for whatever reasons) and you better have to be well prepared because Science is strong on the other side. Only a few years from now, fraud and misconduct was a piece of cake ([Mechanical Turk](https://en.wikipedia.org/wiki/The_Turk), [Piltdown man](https://en.wikipedia.org/wiki/Piltdown_Man), [Water Memory](https://en.wikipedia.org/wiki/Water_memory)). Problem is that there are new players in town ([PubPeer](https://pubpeer.com), [RetractionWatch](http://retractionwatch.com), [For Better Science](https://forbetterscience.com), [Neuroskeptic](http://blogs.discovermagazine.com/neuroskeptic/) to name just a few) and they're pretty good at spotting and reporting fraudsters. To commit fraud or misconduct without getting caught in 2017 is kind of a challenge. But there will be always people that think they're smarter than the whole community. And because we love to have things done in the proper way, we're kind enough to give you some simple rules to follow in your new career. However, results and consequences are not guaranteed.


## 1. Misrepresent, falsify or fabricate your data

   In order to start a plain and deceitful scientific fraudster life, the very first thing you need to gain expertise on is to learn how to convincingly misrepresent, falsify or fabricate your data. If you're still hesitating at embracing the dark side of Science, you may start with a slight mis-representation of you data to strengthen your hypothesis. Some classical techniques are illustrated in the seventh rule of the [Ten Simple Rules for Better Figures](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003833) article but there are actually [many more techniques](https://en.wikipedia.org/wiki/Misleading_graph) to make a graph misleading. You can also directly change your results in a post-production phase by using software such as Photoshop or Gimp that makes it really easy to change pretty much anything in a figure. But be careful of not making too obvious manipulations because an evergrowing number of journals are now equipped with [forensic software]() to [spot image manipulation](http://doi.org/10.1136/bmj.39160.666204.BD) (see also [PLoS image manipulation recommendation](http://journals.plos.org/ploscompbiol/s/figures#loc-image-manipulation)
   and [What's in a picture?](http://jcb.rupress.org/content/166/1/11.figures-only)). You can even test your image online using [Forensically](https://29a.ch/photo-forensics/#forensic-magnifier) by Jonas Wagner. This should dissuade from manipulating your image by yourself.

   Because none of the above techniques will change the statistics behind your data, it might be better indeed to falsify your data. Starting with real data, you can change only a few points in order to change a non-significant results into an astoundingly highly significant result (you can train yourself using the [p-hacker](http://shinyapps.org/apps/p-hacker/) applications by Felix Schönbrodt). The advantage of falsifying real data is that changing only a few points will still make your data looks good and not too much suspicious. The disadvantage is that it requires some real data in the first place and thus it requires to carry on some actual experiment (i.e. some work). As a last resort, you can also fabricate the whole dataset using a specific program. For example, starting from a given X mean/SD, Y mean/SD, and a correlation coefficient, you can generate a [dataset with these precise statistics](https://www.autodeskresearch.com/publications/samestats). Just make sure to not pick the datasaurus set (by [Alberto Cairo](http://www.thefunctionalart.com/2016/08/download-datasaurus-never-trust-summary.html)) as it might look suspicious for a reader if you plot it. By the way, make sure to have a backup story when people will start asking or investigating how/when/where/how did you do perform the experiments or this study. A number of misconducts have been unraveled after an extended interview.

   ![](https://3.bp.blogspot.com/-dYWcbKVsiGY/V8RFmMFnLjI/AAAAAAAAG9Y/Qr_PGmR0V8MhSXb8-rBdAsdciny-oql2ACLcB/s1600/1datasaurus.png)

## 2. Hack your results

   If you are reluctant at manipulating your data, you still have the option of simply hacking your results in order to reach the significance level (a.k.a. p-hacking). But before committing any scientific misconduct, are you sure you need to do so? What is the p value of your NHST (Null Hypothesis Significance Test)? Did you consider using one of the many qualification  proposed by [Matthew Hankin](https://mchankins.wordpress.com/2013/04/21/still-not-significant-2/) to report your results? Can't you use expression such as *nearly acceptable level of significance (p=0.06)*, *very closely brushed the limit of statistical significance (p=0.051)* or *weakly statistically significant (p=0.0557)*?

   However, if you're suffering from a bi-polar p-value disorder (term coined by [Daniel Lakens](http://daniellakens.blogspot.fr/2014/05/the-probability-of-p-values-as-function.html)), you'll want to reach the mythical 0.05 threshold whatever the actual data and consequences. It might actually be much easier than you think because the correct usage of the infamous p-value is hardly understood by a number of students, teachers and researchers ([Misinterpretations of Significance](https://www.dgps.de/fachgruppen/methoden/mpr-online/issue16/art1/haller.pdf)). The current situation is actually so bad that the American Statistical Association had to release a statement to explain the correct usage ([Statisticians issue warning over misuse of P values](http://www.nature.com/news/statisticians-issue-warning-over-misuse-of-p-values-1.19503)) last year and Nature issued some warning on the usage of the p-value ([Statistical errors](http://www.nature.com/news/scientific-method-statistical-errors-1.14700)).
   Consequently, before hacking your results, it might be wise to re-read your classics:

   * [An investigation of the false discovery rate and the misinterpretation of p-values](http://rsos.royalsocietypublishing.org/content/1/3/140216)
   * [False-positive psychology](http://journals.sagepub.com/doi/10.1177/0956797611417632)
   * [Mind your confidence interval](https://theconversation.com/mind-your-confidence-interval-how-statistics-skew-research-results-3186)
   * [Dance of the P-values](https://www.youtube.com/watch?v=ez4DgdurRPg)


   Last, but not least, if you're in psychology, you have to take extra-precaution because this domain has recently raised concerns, especially when it comes to the unusual distribution of p-value smaller than 0.05 ([Distributions of p-values smaller than .05 in psychology: what is going on?](https://peerj.com/articles/1935/)). If you add the [statcheck](http://rpubs.com/michelenuijten/202816) variable into the equation, it might be difficult to achieve a proper hacking of your results. It might be time to reconsider your commitment to the dark side of Science.

   ![](https://imgs.xkcd.com/comics/p_values_2x.png)

## 3. Copy/paste work from others

   You have your (fake) results but you still need to publish them to gain fame and tenure. Writing is a tedious task and might represent a fair amount of work. Writing the state of the art in your domain requires to actually read (what?) what your colleagues have been doing over the past few years. It is a very time consuming task. But if one of these colleagues wrote a nice introduction to the domain or a wonderful state of the art, why bother writing a new one? Why not copy/paste what he/she has written instead? Plagiarism is the nuts and bolts of scientific misconduct ([Science Has A Plagiarism Problem](http://blogs.discovermagazine.com/neuroskeptic/2017/02/03/science-plagiarism-problem/)). Of course, you cannot literally copy paste an excerpt of text from an article to insert it in yours. Just imagine a situation where the reviewer would also be the author of the text being reviewed. Consequently, if you really intend to plagiarize, you'll need to transform the text drastically to avoid detection by humans ([Fighting Plagiarism In Scientific Papers](http://www.science20.com/a_quantum_diaries_survivor/fighting_plagiarism_in_scientific_papers-154460)) and more importantly, to avoid detection by dedicated software ([Plagiarism detection](https://www.elsevier.com/editors/perk/plagiarism-complaints/plagiarism-detection)). These software are used by universities and journals for tracking people just like you. And since their database is really huge, plagiarism is harder and harder. Can you imagine than self-plagiarism is not even allowed for a vast majority of journals? In the end, you really have to improve or innovate in your tecniques and to work very hard ([Plagiarism in scientific publishing](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3558294/)). In the end, faced with such adversarial nature of the situation, writing your very own text might be an easier option.


## 4. Write your own peer-review

  Results and papers are ready and it is now time to submit. Depending on the journal you target, you may still encounter some problem with the review process. If reviewers are a bit too picky, they may ask you annoying questions, be a bit suspicious, request more information, ask for a major revision and or even reject your submission (can you imagine?). After all your hard work at fabricating the data and plagiarized the article, that would be really unfair. Fortunately, there is a simple solution. You can actually make write your own review. How is that possible you may ask? It is incredibly easy. At the time of submission, you will be asked to give name of possible reviewers, just give phony names with corresponding email addresses that will be redirected to your mailbox. You will soon receive an invitation to review and you're then free to write your own review and state how brilliant is your own work. Of course, you'll have to write a review that looks like an actual review. If you're Machiavellian, you will have introduced some factual errors in your manuscript such that you can report them later in your review. Make sure also to not send you review before the editor deadline because as reported by Elizabeth Wager ([107 cancer papers retracted due to peer review fraud](https://arstechnica.com/science/2017/04/107-cancer-papers-retracted-due-to-peer-review-fraud/)), *one of the reasons the editors spotted them was that the reviewers responded on time*. However, editors and publishers  are now well aware of the scam ([The peer-review scam](http://www.nature.com/news/publishing-the-peer-review-scam-1.16400)) and they have taken counter-measure ([Peer-Review Fraud — Hacking the Scientific Publication Process](http://www.nejm.org/doi/full/10.1056/NEJMp1512330)). For example, they do not offer anymore the option to recommend unknwon reviewer or the recommendation is restricted to a list of certified reviewer. If you insist on writing your own peer-review, you'll have to be creative and find a new way to game the system.

  ![](http://phdcomics.com/comics/archive/phd050305s.gif)

## 5. Take advantage of predatory publishers

  If most journals will most likely reject your submission because you've applied some of the rules above and get caught red-handed, you still have opportunities to publish your results in one of the many predatory publishers available on the internet (and the internet only). Such predators will publish just anything ([Get Me Off Your Fucking Mailing List](https://en.wikipedia.org/wiki/International_Journal_of_Advanced_Computer_Technology#Publication_controversy)) and you have a 100% chance to have your article published with a lighting fast review (less than 24h for some "journals"). Finding a predatory publisher used to be easy thanks to the list  created and maintained by Jeffrey Beal. Even if some people (and publishers) have judged this list to be controversial, it was incredibly useful for a lot of people. Unfortunately, this list has closed just a few months ago. But you can now take advantage of the [Think/Check/Submit](http://thinkchecksubmit.org) website that *provides a easy-to-use checklist that researchers can refer to when they are investigating whether a journal can be trusted.* Just take the opposite of their wise recommendations and make sure to **not** pick a journal from the list Open Access Scholarly Publishers Association since these journals have been thoroughly reviewed and can be trusted. For example, if none of your colleagues know the journal, if the editorial board is made of unknown or non-existent people (or [dogs in some cases](http://www.atlasobscura.com/articles/olivia-doll-predatory-journals)) and no address / email / telephone is provided to contact the publisher, you may have knocked at the right door. Of course, you will have to pay exorbitant fees to have your work published, but this is the price to pay to have an expedited and complaisant review (if any review at all). Before making you decision where to publish, make sure to check as well for the retraction fees that may be much higher than the initial publishing fees in some cases. But who want to retract anyway?


## 6. Post-Register your study
## 7. Don't give access to your data

## 8. Never, ever, retract your results

  Retracting a paper is [a lot of hassle](http://retractionwatch.com/2013/06/19/why-i-retracted-my-nature-paper-a-guest-post-from-david-vaux-about-correcting-the-scientific-record/) and you probably
  don't want to lose too much time in trying ([The long road to retraction](http://www.nature.com/nm/journal/v9/n9/full/nm0903-1093.html)). You probably have much better
  things to do like fabricating data for your next ~~study~~ paper.

## 9. Don't get caught. Deny if caught.

  If you intend to persist in your rogue scientific career, you have to know
  that most likely, you'll get caught. The sooner or the later, but it will
  happen eventually. The number of researcher to have never been caught is
  extremely low and only the best can hope to be caught only after their death
  ([Charles Dawson](https://en.wikipedia.org/wiki/Charles_Dawson), doi:10.1098/rsos.160328). But being caught does not mean you career will come to an end. There are
  actually a set of simple rules to deny having committed any scientific
  misconduct.

  * If you're first author, explain you were supervised by last author
  * If you're last author, explain you were not aware of the misconduct
  * If your name appears between first and last, you can try to explain
    you did not know your name appeared in the publication.
  * The intern is responsible (even if your name is last on the publication)
  * My computer with all the proofs has just been stolen from me
  * Send threat letter to those who have spotted your misconduct
  * First add an erratum to the article
  * Sue'em [(Fazlul Sarkar](http://retractionwatch.com/category/by-author/fazlul-sarkar/))


* Over-interpret your data
* Do not allow for replication outside your lab

## Conclusion

  By following the rules above, you should obtain instantaneous and brief scientific glory, possibly followed by a jail sentence (nothing comes for free). In fact, since 2015, scientific misconduct can lead you to jail (57 months in this
  specific case). Science has been poisoned by misconduct and it seems it is now
  fighting back and law is on its side.

---

### Top 10 Retractions

* [Publish or Perish (3) – Fraud and ethics](http://www.alfredhartemink.nl/PDF/3.%20Fraud%20and%20ethics.pdf)
* [The Top 10 Retractions of 2016](http://www.the-scientist.com/?articles.view/articleNo/47813/title/Top-10-Retractions-of-2016/)
* [The Top 10 Retractions of 2015](http://www.the-scientist.com/?articles.view/articleNo/44895/title/The-Top-10-Retractions-of-2015/)
* [The Top 10 Retractions of 2014](http://www.the-scientist.com/?articles.view/articleNo/41777/title/The-Top-10-Retractions-of-2014/)
* [The Top 10 Retractions of 2013](http://www.the-scientist.com/?articles.view/articleNo/38743/title/Top-10-Retractions-of-2013/)
* [Top Science Scandals of 2012](http://www.the-scientist.com/?articles.view/articleNo/33695/title/Top-Science-Scandals-of-2012/)
* [The 10 Greatest Cases of Fraud in University Research (2012)](http://www.onlineuniversities.com/blog/2012/02/the-10-greatest-cases-of-fraud-in-university-research/)
* [Top 10 Scientific Frauds and Hoaxes (2008)](http://listverse.com/2008/04/09/top-10-scientific-frauds-and-hoaxes/)

### Famous case
* [Jan Hendrik Schön (2002)](http://www.science20.com/science_20/jan_hendrik_schön_world_class_physics_fraud_gets_last_laugh_whole_book_about_himself)
* [Olivier Voinnet (2013)](http://retractionwatch.com/2015/01/09/award-winning-plant-researcher-correcting-several-papers-critiqued-pubpeer/)
* [Dong-Pyou Han (2015)](http://www.the-scientist.com/?articles.view/articleNo/43456/title/Vaccine-Fraudster-Gets-Jail-Time/)
* [Diederik Stapel (2011)](https://www.washingtonpost.com/blogs/achenblog/post/diederik-stapel-the-lying-dutchman/2011/11/01/gIQA86XOdM_blog.html)
* [Michael Lacour (2013)](http://nymag.com/scienceofus/2015/05/how-a-grad-student-uncovered-a-huge-fraud.html)

### See also

* [Same Stats, Different Graphs](https://www.autodeskresearch.com/publications/samestats)
* [The Rules of the Game Called Psychological Science](http://journals.sagepub.com/doi/abs/10.1177/1745691612459060)
* [The promise of pre-registration in psychological research](http://www.apa.org/science/about/psa/2015/08/pre-registration.aspx)
* [Fraud Breeds Retractions](http://www.the-scientist.com/?articles.view/articleNo/32687/title/Fraud-Breeds-Retractions/)
* [US vaccine researcher sentenced to prison for fraud](http://www.nature.com/news/us-vaccine-researcher-sentenced-to-prison-for-fraud-1.17660)
* [Scientific Integrity In The Age of Photoshop](http://www.hopkinsmedicine.org/institute_basic_biomedical_sciences/news_events/articles_and_stories/employment/2011_01_scientific_integrity.html)
* [Science Fraud](https://explorable.com/science-fraud)
* [The hi-tech war on science fraud](https://www.theguardian.com/science/2017/feb/01/high-tech-war-on-science)
* [P-Hacker](http://shinyapps.org/apps/p-hacker)
* [The lessons of famous science frauds](https://www.theverge.com/2015/6/9/8749841/science-frauds-potti-lacour)
* [How to Publish a Scientific Comment in 123 Easy Steps](http://frog.gatech.edu/Pubs/How-to-Publish-a-Scientific-Comment-in-123-Easy-Steps.pdf)
