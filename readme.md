# Research papers [![Lists](https://img.shields.io/badge/-more%20lists-0a0a0a.svg?style=flat&colorA=0a0a0a)](https://github.com/learn-anything/curated-lists)

The number after the name stands for the year in which the research paper was written in. All research papers are put in their respective category and are sorted from newest to oldest.

_Please read [contribution guidelines](contributing.md) before contributing._

- [Artificial intelligence](#artificial-intelligence)
- [Big Data](#big-data)
- [Category theory](#category-theory)
- [Compilers](#compilers)
- [Computer science](#computer-science)
- [Computer vision](#computer-vision)
- [Concurrency](#concurrency)
- [Databases](#databases)
- [Deep Learning](#deep-learning)
- [Design](#design)
- [Functional programming](#functional-programming)
- [Garbage collection](#garbage-collection)
- [Haskell](#haskell)
- [Machine Learning](#machine-learning)
- [Math](#math)
- [Neural networks](#neural-networks)
- [Operating systems](#operating-systems)
- [Physics](#physics)
- [Programming languages](#programming-languages)
- [Programming](#programming)
- [Psychedelics](#psychedelics)
- [Reverse engineering](#reverse-engineering)
- [Security](#security)
- [Statistics](#statistics)
- [System design](#system-design)
- [Type theory](#type-theory)
- [Virtualization](#virtualization)
- [Web](#web)
- [Other](#other)
- [Related](#related)

## Artificial intelligence

- [Winner-take-all autoencoders](https://arxiv.org/pdf/1409.2752.pdf)
- [A roadmap towards machine intelligence](https://arxiv.org/pdf/1511.08130.pdf)
- [Is the brain a good model for machine intelligence?](http://www.gatsby.ucl.ac.uk/%7Edemis/TuringSpecialIssue%28Nature2012%29.pdf)
- [Concrete problems in ai safety](https://arxiv.org/pdf/1606.06565.pdf)

## Big Data

- [The pathologies of big data](http://queue.acm.org/detail.cfm?id=1563874)

## Category theory

- [Backprop as Functor: A compositional perspective on supervised learning - Brendan Fong, David I. Spivak, Rémy Tuyéras (2017)](https://arxiv.org/abs/1711.10455)
- [The Algebra of Open and Interconnected Systems - Brendan Fong (2016)](https://arxiv.org/abs/1609.05382)

## Compilers

- [Writing parsers like it is 2017](http://spw17.langsec.org/papers/chifflier-parsing-in-2017.pdf)
- [Calculating correct compilers (2015)](http://www.cs.nott.ac.uk/%7Epszgmh/ccc.pdf)
- [An incremental approach to compiler construction](http://scheme2006.cs.uchicago.edu/11-ghuloum.pdf)
- [Dynamo: a transparent dynamic optimization system](https://www.cs.virginia.edu/kim/courses/cs771/papers/bala00dynamo.pdf)

## Computer science

- [The Case for Learned Index Structures (2017)](https://www.arxiv-vanity.com/papers/1712.01208/)
- [Squeak makes a good python debugger (2017)](https://github.com/fniephaus/papers/blob/master/2017/px17-debugger.pdf)
- [Dat - Distributed Dataset Synchronisation and Versioning (2017)](https://github.com/datproject/docs/blob/master/papers/dat-paper.pdf)
- [Robots take over the world (2007)](http://cseweb.ucsd.edu/classes/fa16/cse200-a/robots_rule.pdf)
- [Let’s go to the whiteboard: (2007)](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/p557-cherubini.pdf)
- [How and why software developers use drawings](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/p557-cherubini.pdf)
- [How complex systems fail](http://web.mit.edu/2.75/resources/random/How%20Complex%20Systems%20Fail.pdf)
- [How to make ad-hoc polymorphism less ad hoc](https://people.csail.mit.edu/dnj/teaching/6898/papers/wadler88.pdf)
- [Challenges to adopting stronger consistency at scale](http://www-bcf.usc.edu/~wyattllo/papers/challenges-hotos15.pdf)
- [Naked objects](http://downloads.nakedobjects.net/resources/Pawson%20thesis.pdf)
- [Three measurement problems](https://www.academia.edu/32885328/Three_measurement_problems)
- [A hub-based labeling algorithm for shortest paths on road networks](https://www.microsoft.com/en-us/research/wp-content/uploads/2010/12/HL-TR.pdf)

## Computer vision

- [An analysis of single-layer networks in unsupervised feature learning](http://ai.stanford.edu/%7Eacoates/papers/coatesleeng_aistats_2011.pdf) - Interesting paper about how using weaker classifiers (kmeans) can get comparable results to more sophisticated ones like deep neural nets with the decisions made before training a model like statistical whitening, picking a large number of features, etc.
- [Viola jones robust real-time object detection](http://www.swarthmore.edu/NatSci/mzucker1/papers/violaJones_IJCV.pdf) - Real time face detection method most cameras use today, discusses ensemble learning methods (adaboost) and a clever way to detect features in one O(n) pre-processing step.
- [Example-based photometric stereo: shape reconstruction with general, varying brdfs](http://grail.cs.washington.edu/projects/sam/HertzmannSeitzPAMI2005.pdf) - Discusses how you can reconstruct an objects 3d shape just by analyzing how light reflects off an object's surface.
- [Mask r-cnn](https://arxiv.org/abs/1703.06870)

## Concurrency

- [Beautiful concurrency (2007)](https://www.microsoft.com/en-us/research/publication/beautiful-concurrency/)

## Databases

- [Simplicial Databases - David I. Spivak (2009)](https://arxiv.org/abs/0904.2012)

## Deep Learning

- [Evolution strategies as a scalable alternative to reinforcement learning (2017)](https://arxiv.org/abs/1703.03864)

## Design

- [Yond human abilities](https://dreamsongs.com/Files/DesignBeyondHumanAbilitiesSimp.pdf)

## Functional programming

- [How to make ad-hoc polymorphism less ad hoc (1988)](https://pdfs.semanticscholar.org/cc7f/2242dba6f09023128897762d07517f13ba4a.pdf)
- [Lazy functional state threads (1994)](https://www.microsoft.com/en-us/research/wp-content/uploads/1994/06/lazy-functional-state-threads.pdf) - Accessible introduction to the machinery underneath ST and IO.
- [The countdown problem (2002)](http://www.cs.nott.ac.uk/%7Epszgmh/countdown.pdf)
- [Functional program to solve sudoku (2006)](http://www.cs.tufts.edu/%7Enr/cs257/archive/richard-bird/sudoku.pdf)
- [Infinite sets that admit fast exhaustive search (2007)](http://www.cs.bham.ac.uk/%7Emhe/papers/exhaustive.pdf)
- [Applicative programming with effects (2008)](http://www.staff.city.ac.uk/%7Eross/papers/Applicative.html)
- [Data types a la carte (2008)](http://www.cs.ru.nl/%7EW.Swierstra/Publications/DataTypesALaCarte.pdf)
- [Parallel Functional Arrays (2017)](http://www.cs.cmu.edu/%7Erwh/papers/farray/popl17.pdf)
- [Trees that grow](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/11/trees-that-grow.pdf)
- [Super compilation by evaluation](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/07/supercomp-by-eval.pdf)
- [Cache Efficient Functional Algorithms](http://www.cs.cmu.edu/%7Erwh/papers/iolambda-cacm/cacm.pdf)
- [Breaking through the normalisation barrier: a self-interpreter for f-omega](http://compilers.cs.ucla.edu/popl16/)
- [Typed self-evaluation via intensional type functions](http://compilers.cs.ucla.edu/popl17/)
- [Freer monads, more extensible effects](http://okmij.org/ftp/Haskell/extensible/more.pdf)
- [The Genuine Sieve of Eratosthenes](https://www.cs.hmc.edu/~oneill/papers/Sieve-JFP.pdf)

## Garbage collection

- [Lively linear lisp -- 'look ma, no garbage!](http://www.pipeline.com/~hbaker1/LinearLisp.html)
- [Thermodynamics and garbage collection](http://www.pipeline.com/~hbaker1/ThermoGC.html)

## Haskell

- [Linear-Time Suffix Array Implementation in Haskell (2014)](http://www.scs.stanford.edu/14sp-cs240h/projects/isaacs_geiduscheck.pdf)

## Machine Learning

- [AutoAugment: Learning Augmentation Policies from Data (2018)](https://arxiv.org/abs/1805.09501)
- [Mastering Chess and Shogi by Self-Play with a General Reinforcement Learning Algorithm (2017)](https://arxiv.org/abs/1712.01815)
- [Neural Machine Translation and Sequence-to-sequence Models: A Tutorial (2017)](https://arxiv.org/abs/1703.01619)
- [Deep voice: real-time neural text-to-speech (2017)](https://arxiv.org/pdf/1702.07825.pdf)
- [Dropout: a simple way to prevent neural networks from overfitting (2014)](https://www.cs.toronto.edu/~hinton/absps/JMLRdropout.pdf)
- [A Unifying Review of Linear Gaussian Models (1998)](http://mlg.eng.cam.ac.uk/zoubin/papers/lds.pdf)
- [Gaussian processes for big data](http://auai.org/uai2013/prints/papers/244.pdf)
- [Adversarial Patch](https://arxiv.org/pdf/1712.09665.pdf)
- [A few useful things to know about machine learning](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)
- [The high-interest credit card of technical debt](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/43146.pdf)
- [InfoGAN: Interpretable Representation Learning by Information Maximizing Generative Adversarial Nets](https://arxiv.org/pdf/1606.03657.pdf)

## Math

- [Polynomial exact-3-sat solving algorithm](http://vixra.org/pdf/1212.0109v1.pdf)
- [The language and grammar of mathematics](http://press.princeton.edu/chapters/gowers/gowers_I_2.pdf)
- [Comprehending Monads](https://ncatlab.org/nlab/files/WadlerMonads.pdf)
- [Notation as a tool of thought](http://www.jsoftware.com/papers/tot.htm)
- [A Mathematical Theory of Communication](http://math.harvard.edu/~ctm/home/text/others/shannon/entropy/entropy.pdf)
- [Graph isomorphism in quasipolynomial time](https://arxiv.org/abs/1512.03547)
- [On proof and progress in mathematics](https://arxiv.org/pdf/math/9404236v1.pdf)
- [Introduction to categories and categorical logic](https://arxiv.org/abs/1102.1313)
- [A notion of a computational step for partial combinatory algebras](http://math.mit.edu/~freer/papers/AF-stepalg.pdf)
- [Reading mathematics](http://www.math.cornell.edu/~hubbard/readingmath.pdf)
- [Quotients homophones des groupes libres homophonic quotients of free groups](http://people.mpim-bonn.mpg.de/zagier/files/exp-math-2/fulltext.pdf)
- [A beginner’s guide to forcing](https://arxiv.org/pdf/0712.1320.pdf)
- [A lagrangian dual approach to the generalized kyp lemma](https://pdfs.semanticscholar.org/acdc/f72a08e4847f4e0ab2e7cf0d58bd4d8ded92.pdf)
- [What is good mathematics? (2007)](https://arxiv.org/abs/math/0702396)
- [On the dimensionality of spacetime](https://arxiv.org/pdf/gr-qc/9702052.pdf)
- [A cohomological viewpoint on elementary school arithmetic](http://www.math.wayne.edu/~isaksen/Expository/carrying.pdf)
- [Beta reduction is invariant, indeed](https://arxiv.org/abs/1601.01233)
- [Sketch of a Programme](http://matematicas.unex.es/%7Enavarro/res/esquisseeng.pdf)
- [A naturalist account of the limited, and hence reasonable, effectiveness of mathematics in physics (2015)](https://arxiv.org/abs/1506.03733)

## Neural networks

- [Neural Ordinary Differential Equations (2018)](https://arxiv.org/abs/1806.07366)
- [Neural networks and deep learning](http://neuralnetworksanddeeplearning.com/)
- [Learning without forgetting](https://arxiv.org/pdf/1606.09282.pdf)
- [Neural turing machine](http://en.wikipedia.org/wiki/Neural_Turing_machine)
- [Densely connected convolutional networks](https://arxiv.org/abs/1608.06993)
- [Overcoming catastrophic forgetting in neural networks](http://www.pnas.org/content/early/2017/03/13/1611835114.full.pdf)
- [Pathnet: evolution channels gradient descent in super neural networks](https://arxiv.org/pdf/1701.08734.pdf)

## Operating systems

- [NixOS: A purely Functional Linux Distribution (2010)](https://nixos.org/%7Eeelco/pubs/nixos-jfp-final.pdf)
- [Urbit: A Solid-State Interpreter (2016)](http://media.urbit.org/whitepaper.pdf)

## Physics

- [Hamiltonian for the zeros of the Riemann Zeta function (2016)](https://arxiv.org/abs/1608.03679)
- [General Relativity and Cosmology: Unsolved Questions and Future Directions (2016)](https://arxiv.org/abs/1609.09781)
- [There are no particles, there are only fields (2012)](https://arxiv.org/abs/1204.4616)
- [Would Bohr be born if Bohm were born before Born? (2007)](https://arxiv.org/abs/physics/0702069)
- [The holographic solution - why general relativity must be understood in terms of strings (2004)](https://arxiv.org/abs/gr-qc/0405007)
- [Measurement of subpicosecond time intervals between two photons by Interference (1987)](https://www.colorado.edu/physics/phys7810_006/phys7810_006_sp13/QuantumOptics_sp13/Lectures_files/HOM_PRL_1987.pdf)
- [Bertlmann’s socks and the nature of reality (1981)](https://hal.archives-ouvertes.fr/file/index/docid/220688/filename/ajp-jphyscol198142C202.pdf)
- [More is different (1972)](https://www.physics.ohio-state.edu/~jay/880/moreisdifferent.pdf)
- [On the Einstein Podolsky Rosen Paradox (1964)](http://cds.cern.ch/record/111654/files/vol1p195-200_001.pdf)
- [Deterministic Nonperiodic Flow (1962)](http://eaps4.mit.edu/research/Lorenz/Deterministic_63.pdf)
- [There's Plenty of Room at the Bottom (1959)](http://www.zyvex.com/nanotech/feynman.html)
- [Forms of Relativistic Dynamics (1949)](https://journals.aps.org/rmp/abstract/10.1103/RevModPhys.21.392)
- [What is life? (1944)](http://www.whatislife.ie/downloads/What-is-Life.pdf)
- [Can Quantum-Mechanical Description of Physical Reality Be Considered Complete? (1935)](https://journals.aps.org/pr/pdf/10.1103/PhysRev.47.777)
- [Possible Existence of a Neutron (1932)](http://web.mit.edu/22.54/resources/Chadwick.pdf)
- [On the electrodynamics of moving bodies (1905)](http://hermes.ffn.ub.es/luisnavarro/nuevo_maletin/Einstein_1905_relativity.pdf)

## Programming languages

- [Using closures for code generation](http://www.iro.umontreal.ca/%7Efeeley/papers/FeeleyLapalmeCL87.pdf)

## Programming

- [Scripting: higher level programming for the 21st century](http://web.stanford.edu/~ouster/cgi-bin/papers/scripting.pdf)
- [Notes on postmodern programming](http://www.mcs.vuw.ac.nz/comp/Publications/CS-TR-02-9.abs.html)
- [Recursive make considered harmful](https://web.archive.org/web/20070205051133/http://members.canb.auug.org.au/~millerp/rmch/recu-make-cons-harm.html)
- [Kademlia: a peer-to-peer information system based on the xor metric](http://www.scs.stanford.edu/~dm/home/papers/kpos.pdf)
- [Equal rights for functional objects or, the more things change, the more they are the same](http://home.pipeline.com/~hbaker1/ObjectIdentity.html)
- [What every programmer should know about memory](https://www.akkadia.org/drepper/cpumemory.pdf)
- [The c standard formalised in coq](http://robbertkrebbers.nl/research/thesis.pdf)
- [An analysis and survey of the development of Mutation testing](https://pdfs.semanticscholar.org/3277/8a2eb4c74cd437e922ac1eb6a1477dfcb925.pdf)
- [The Purely Functional Software Deployment Model](https://nixos.org/%7Eeelco/pubs/phd-thesis.pdf)

## Psychedelics

- [Crystal structure of an lsd-bound human serotonin receptor](http://www.cell.com/cell/fulltext/S0092-8674%2816%2931749-4)
- [Towards a biophysical understanding of hallucinogen action (2007)](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.688.8514&rep=rep1&type=pdf)

## Reverse engineering

- [Reverse compilation techniques](https://yurichev.com/mirrors/DCC_decompilation_thesis.pdf)

## Security

- [Some thoughts on security after ten years of qmail 1.0](http://cr.yp.to/qmail/qmailsec-20071101.pdf)
- [Comparative Analysis of Machine-Learning IDS methodologies to detect DDOS (2019)](https://repository.stcloudstate.edu/msia_etds/91/)

## Statistics

- [Probabilistic machine learning and artificial intelligence](http://www.nature.com/nature/journal/v521/n7553/full/nature14541.html)

## System design

- [Systems approaches to tackling configuration errors: a survey](http://opera.ucsd.edu/paper/csur15-survey.pdf)

## Type theory

- [The Syntax and Semantics of Quantitative Type Theory (2018)](https://bentnib.org/quantitative-type-theory.html)
- [Computational Higher Type Theory I: Abstract Cubical Realizability (2016)](https://arxiv.org/abs/1604.08873)
- [Cubical Type Theory: a constructive interpretation of the univalence axiom (2016)](https://arxiv.org/abs/1611.02108)
- [Lambda Calculi with Types (1992)](http://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=97EC80F28ED10845C2941C0BFB8AC432?doi=10.1.1.26.4391&rep=rep1&type=pdf)
- [Propositions as types](http://homepages.inf.ed.ac.uk/wadler/papers/propositions-as-types/propositions-as-types.pdf)
- [The derivative of a regular type is its type of one-hole contexts](http://strictlypositive.org/diff.pdf)
- [On the meanings of the logical constants and the justifications of the logical laws ](https://uberty.org/wp-content/uploads/2017/06/Martin-Lof83.pdf)

## Virtualization

- [Virtual machine monitors: current technology and future trends](http://xenon.stanford.edu/%7Etalg/papers/COMPUTER05/virtual-future-computer05.pdf)

## Web

- [Breaking the browser language barrier (2017)](http://plasma-umass.github.io/doppio-demo/paper.pdf)

## Other

- [Tor: The Second-Generation Onion Router](https://svn.torproject.org/svn/projects/design-paper/tor-design.pdf)

## Related

- [arXiv](https://arxiv.org/)
- [Papers we love](http://paperswelove.org/)
- [arXiv sanity preserver](http://www.arxiv-sanity.com/)
- [Research in production](https://github.com/evnm/research-in-production)
- [Awesome deep learning papers](https://github.com/endymecy/awesome-deeplearning-resources)
- [Summaries and notes on deep learning research papers](https://github.com/dennybritz/deeplearning-papernotes)
- [Google Brain Team](https://research.google.com/teams/brain)
- [Inspire](https://inspirehep.net)
- [PLOS](https://www.plos.org)
- [Apple Machine Learning Research](https://machinelearning.apple.com/)

[![CC4](https://img.shields.io/badge/license-CC4-0a0a0a.svg?style=flat&colorA=0a0a0a)](https://creativecommons.org/licenses/by/4.0/)
[![Lists](https://img.shields.io/badge/-more%20lists-0a0a0a.svg?style=flat&colorA=0a0a0a)](https://github.com/learn-anything/curated-lists)
[![Contribute](https://img.shields.io/badge/-contribute-0a0a0a.svg?style=flat&colorA=0a0a0a)](contributing.md)
[![Twitter](http://bit.ly/latwitt)](https://twitter.com/learnanything_)
