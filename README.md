# ML4SE Seminar Papers

## List of papers to read
- Andrew Scott, Johannes Bader, Satish Chandra
  "Getafix Learning to fix bugs automatically"
  arxiv 2019.
- Sifei Luan, Di Yang, Koushik Sen, Satish Chandra
  "Aroma: Code Recommendation via Structural Code Search." 
  arXiv 2018.
- Saksham Sachdev, Hongyu Li, Sifei Luan, Seohyun Kim, Koushik Sen, and Satish Chandra. 
  "Retrieval on source code: a neural code search." 
  International Workshop on Machine Learning and Programming Languages (MAPL 2018).
- Wang, Ke, Rishabh Singh, and Zhendong Su. 
  "Dynamic Neural Program Embeddings for Program Repair."
  ICLR 2018.
- Ray, Baishakhi, Vincent Hellendoorn, Saheel Godhane, Zhaopeng Tu, Alberto Bacchelli, and Premkumar Devanbu. 
  "On the" naturalness" of buggy code." 
  ICSE 2016
- M. Brockschmidt, M. Allamanis, A. L. Gaunt, O. Polozov. 
  "Generative Code Modeling with Graphs."
  ICLR 2019
- Xinyun Chen, Chang Liu, Dawn Song
  "Tree-to-tree Neural Networks for Program Translation." 
  NeurIPS 2018
- Anshul Gupta and Neel Sundaresan.
  "Intelligent code reviews using deep learning"
  KDD 2018
- Riley Simmons-Edler, Anders Miltner, Sebastian Seung:
  "Program Synthesis Through Reinforcement Learning Guided Tree Search." 
  arxiv (2018)
- Alexander L. Gaunt, Marc Brockschmidt, Rishabh Singh, Nate Kushman, Pushmeet Kohli, Jonathan Taylor, Daniel Tarlow
  "TerpreT: A Probabilistic Programming Language for Program Induction"
  arxiv (2016)

## List of read papers

### [Feb 15th, 2019] DeepCoder: Learning to Write Programs
Authors: Matej Balog, Alexander L. Gaunt, Marc Brockschmidt, Sebastian Nowozin, Daniel Tarlow.
Venue: ICLR
Year: 2017
Labels: Program Synthesis, Programming By Example, Deep Learning
Summary:
- DeepCoder is a technique to augment Inductive Program Synthesis
  (IPS), by guiding the synthesis with a deep neural network that
  predicts a set of functions that should be present in the program. A
  model is trained based on synthetically generated programs and
  coresponding input-output examples. To constrain the search space
  they define a DSL in which they synthesize programs.
  + Good Evaluation
  + Nice illustration of embeddings in 2d
  + Discussion of limitations
Limitations (Open Questions): 
- Works for very small programs.
- Data Generation. They use synthetic examples for training and
  evaluation; how does this generalize to realistic programs.
- As number of problems solved increases, Deepcoder speedup decreases
  compared to a baseline. Why is this the case, does the order of
  programs being solved matter.
Possible related work to read:
- Learning Syntactic Program Transformations from Examples
- TerpreT: A Probabilistic Programming Language for Program Induction

### [Feb 15th, 2019] Structured generative models of natural source code
Authors: Maddison, Chris, and Daniel Tarlow. 
Venue: ICML
Year: 2014
Summary:
- They build a generative model of source code using improvement of
  PCFG, as well as a PCFG for a baseline.
