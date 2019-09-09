---
layout: default
---

Michael Wick is a senior member of the technical staff in the Machine Learning Research Group at Oracle Labs in Burlington MA.  His research interests lie at the intersection of machine learning and natural language processing with a proclivity for probabilistic modeling, a family of techniques, I've been told, now relegated to the study of the antiquarian. As of March 2019, [Google Scholar](https://scholar.google.com/citations?user=D0DpJUwAAAAJ&hl=en&oi=ao) estimates he has 60 papers, nearly 1000 citations, and an h-index of 17.  Among other things, he's interested in studying ways of exploiting the natural structure in large quantities of unlabeled data via generative models parameterized by high capacity learners (i.e., neural nets), and is especially interested in studying the limits of such approaches with the hope that these limits, or failure modes, will provide insight into the models' missing inductive biases so we can goad them to do better.

Prior to joining Oracle Labs he did his Ph.D. with [Andrew McCallum](https://people.cs.umass.edu/~mccallum/) at the University of Massachusetts.  There he focused on challenging information extraction problems that drove research in developing the types of computationally efficient probabilistic learning and inference algorithms necessary to solve them.  Many of the techniques developed for these problems, such as SampleRank training, helped make possible the general purpose probabilistic programming toolkit [FACTORIE](http://factorie.cs.umass.edu), which allows a data scientist to specify nearly arbitrary conditional random fields while still supporting efficient learning and inference.  His dissertation *Epistemological Databases for Probabilistic Knowledge Base Construction* [[pdf]](https://scholarworks.umass.edu/cgi/viewcontent.cgi?article=1338&context=dissertations_2) harnessed FACTORIE and made progress towards continual incremental KB construction via never-ending probabilistic inference.  He is recipient of the Yahoo! [Key Scientific Challenges Award](https://www.umass.edu/newsoffice/article/yahoo-names-key-scientific-challenge-winners) in 2010, and the Award for Excellence in Search and Mining in 2009.  He co-organized two ICML workshops on [the interactions between inference and learning (Inferening)](http://inferning.cs.umass.edu/) in [2012](http://inferning.cs.umass.edu/2012) and [2013](http://inferning.cs.umass.edu/2013).



### News

Michael is an Area Chair for the first annual Conference on [Automated Knowledge Base construction (AKBC)](http://www.akbc.ws/2019/) 2019, to take place in the resplendent Amherst, MA.  Hope to see you all there.

Our paper on gradient-based inference was presented at AAAI.

Our paper on scaling probabilistic models with linear homomorphic compression was accepted at AKBC.

Our paper on sketching algorithms for scaling latent Dirichlet-Categorical models was accepted at AISTATS.

### Selected and Recent Publications
Michael Wick, Swetasudha Panda, Jean-Baptiste Tristan.  *Unleashing Fairness: a Trade-off Revisited*  NeurIPS 2019 (to appear). [[pdf]](comingsoon.pdf)


Jay Yoon Lee, Sanket Mehta, Michael Wick, Jean-Baptiste Tristan, Jaime Carbonell.  *Gradient-based inference for networks with output constraints.*  AAAI 2019. [[pdf]](https://www.aaai.org/Papers/AAAI/2019/AAAI-LeeJ.6432.pdf)

Michael Wick, Swetasudha Panda, Joseph Tassarotti, Jean-Baptiste Tristan.  *Scaling hierarchical coreference with homomorphic compression.*  AKBC 2019 (in preperation).

Joseph Tassarotti, Jean-Baptiste Tristan, Michael Wick.  *Sketching for latent Dirichlet-categorical models.*  AISTATS 2019 (in preperation).


Manzil Zaheer, Michael Wick, John Tristan, Alex Smola, Guy Steele.  *Exponential stochastic cellular automata for massively parallel inference.*  AISTATS 2016. [[pdf]](http://proceedings.mlr.press/v51/zaheer16.pdf)

Michael Wick, Pallika Kanani, Adam Pocock. *Minimally-constrained multilingual embeddings via artificial code switching.*  AAAI 2016. [[pdf]](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/viewFile/12464/12032)

Michael Wick, Kashayar Rohanimanesh, Kedar Bellare, Aron Culotta, Andrew McCallum. *SampleRank: training factor graphs with atomic gradients.  ICML 2011.* [[pdf]](http://www.cs.iit.edu/~culotta/pubs/wick09sample.pdf)

Michael Wick, Andrew McCallum.  *Query-aware MCMC.*  NuerIPS 2011. [[pdf]](https://papers.nips.cc/paper/4237-query-aware-mcmc.pdf)

Michael Wick, Gerome Miklau, Andrew McCallum.  *Scalable probabilistic databases with factor graphs and MCMC*.  VLDB 2010. [[pdf]](http://www.vldbarc.org/pvldb/vldb2010/pvldb_vol3/R71.pdf)

Sameer Singh, Michael Wick, Andrew McCallum. *Monte Carlo MC: Efficient inference by approximate sampling.*  EMNLP 2012. [[pdf]](https://ciir-publications.cs.umass.edu/getpdf.php?id=1053)

Andrew McCallum, Kashayar Rohanimanesh, Michael Wick, Karl Schultz, Sameer Singh.  *Factorie: efficient probabilistic programming via imperative declarations of structure, inference and learning.*  NeurIPS workshop on probabilistic programming 2008. [[pdf]](http://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=3074A767BA2B302122B17414340C1AD8?doi=10.1.1.219.2011&rep=rep1&type=pdf) 
