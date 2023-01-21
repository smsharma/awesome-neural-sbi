# Awesome Neural SBI

A community-sourced list of papers and resources on neural simulation-based inference.

# Code and resources

- [`sbi`](https://github.com/mackelab/sbi) [[Paper]](https://joss.theoj.org/papers/10.21105/joss.02505): General-purpose simulation-based inference toolkit.
- [`sbibm`](https://github.com/sbi-benchmark/sbibm) [[Paper]](https://arxiv.org/abs/2101.04653): Simulation-based inference benchmarking framework.
- [`swyft`](https://github.com/undark-lab/swyft) [[Paper]](https://joss.theoj.org/papers/10.21105/joss.04205): Official implementation of Truncated Marginal Neural Ratio Estimation (TMNRE), a hyper-efficient, simulation-based inference technique for complex data and expensive simulators. 
- [`lampe`](https://github.com/francois-rozet/lampe): Likelihood-free AMortized Posterior Estimation with PyTorch
- [`MadMiner`](https://github.com/madminer-tool/madminer) [[Paper]](https://arxiv.org/abs/1907.10621): Machine learning–based inference toolkit for particle physics
- [`pydelfi`](https://github.com/justinalsing/pydelfi) [[Paper]](https://arxiv.org/abs/1903.00007): Density Estimation Likelihood-Free Inference (DELFI) with neural density estimators and adaptive acquisition of simulations.
- [`carl`](https://github.com/diana-hep/carl) [[Paper]](https://joss.theoj.org/papers/10.21105/joss.00011): An early toolbox for neural network-based likelihood-free inference in Python.
  
## Code packages and benchmarks

## Review papers

## Links

# Theory and methods

- **Monte Carlo Techniques for Addressing Large Errors and Missing Data in Simulation-based Inference** [[arXiv]](https://arxiv.org/abs/2211.03747)  
Bingjie Wang, Joel Leja, Ashley Villar, Joshua S. Speagle

- **Validation Diagnostics for SBI algorithms based on Normalizing Flows** [[arXiv]](https://arxiv.org/abs/2211.01126)  
Julia Linhart, Alexandre Gramfort, Pedro L. C. Rodrigues

- **Likelihood-free hypothesis testing** [[arXiv]](https://arxiv.org/abs/2211.01126)  
Patrik Róbert Gerber, Yury Polyanskiy

- **Maximum Likelihood Learning of Energy-Based Models for Simulation-Based Inference** [[arXiv]](https://arxiv.org/abs/2210.14756)  
Pierre Glaser, Michael Arbel, Arnaud Doucet, Arthur Gretton

- **Efficient identification of informative features in simulation-based inference** [[arXiv]](https://arxiv.org/abs/2210.11915)  
Jonas Beck, Michael Deistler, Yves Bernaerts, Jakob Macke, Philipp Berens

- **Robust Neural Posterior Estimation and Statistical Model Criticism** [[arXiv]](https://arxiv.org/abs/2210.06564)  
Daniel Ward, Patrick Cannon, Mark Beaumont, Matteo Fasiolo, Sebastian M Schmon

- **Contrastive Neural Ratio Estimation** [[arXiv]](https://arxiv.org/abs/2210.06170)  
Benjamin Kurt Miller, Christoph Weniger, Patrick Forré

- **Sequential Neural Score Estimation: Likelihood-Free Inference with Conditional Score Based Diffusion Models** [[arXiv]](https://arxiv.org/abs/2210.04872)  
Louis Sharrock, Jack Simons, Song Liu, Mark Beaumont

- **Truncated proposals for scalable and hassle-free simulation-based inference** [[arXiv]](https://arxiv.org/abs/2210.04815)  
Michael Deistler, Pedro J Goncalves, Jakob H Macke

- **Score Modeling for Simulation-based Inference** [[arXiv]](https://arxiv.org/abs/2209.01845)  
Tomas Geffner, George Papamakarios, Andriy Mnih

- **Investigating the Impact of Model Misspecification in Neural Simulation-based Inference** [[arXiv]](https://arxiv.org/abs/2209.01845)  
Patrick Cannon, Daniel Ward, Sebastian M. Schmon

- **Towards Reliable Simulation-Based Inference with Balanced Neural Ratio Estimation** [[arXiv]](https://arxiv.org/abs/2208.13624)  
Arnaud Delaunoy, Joeri Hermans, François Rozet, Antoine Wehenkel, Gilles Louppe

- **Likelihood-Free Inference with Generative Neural Networks via Scoring Rule Minimization** [[arXiv]](https://arxiv.org/abs/2205.15784)  
Lorenzo Pacchiardi, Ritabrata Dutta

- **Simulation-Based Inference with Waldo: Confidence Regions by Leveraging Prediction Algorithms or Posterior Estimators for Inverse Problems** [[arXiv]](https://arxiv.org/abs/2205.15680)  
Luca Masserano, Tommaso Dorigo, Rafael Izbicki, Mikael Kuusela, Ann B. Lee

- **Learning Optimal Test Statistics in the Presence of Nuisance Parameters** [[arXiv]](https://arxiv.org/abs/2203.13079)  
Lukas Heinrich

- **GATSBI: Generative Adversarial Training for Simulation-Based Inference** [[arXiv]](https://arxiv.org/abs/2203.06481)  
Poornima Ramesh, Jan-Matthis Lueckmann, Jan Boelts, Álvaro Tejero-Cantero, David S. Greenberg, Pedro J. Gonçalves, Jakob H. Macke

- **Variational methods for simulation-based inference** [[arXiv]](https://arxiv.org/abs/2203.04176)  
Manuel Glöckler, Michael Deistler, Jakob H. Macke

- **Robust Bayesian Inference for Simulator-based Models via the MMD Posterior Bootstrap** [[arXiv]](https://arxiv.org/abs/2202.04744)  
Charita Dellaporta, Jeremias Knoblauch, Theodoros Damoulas, François-Xavier Briol

- **Flexible and efficient simulation-based inference for models of decision-making** [[bioRxiv]](https://arxiv.org/abs/2111.13139)  
Jan Boelts, Jan-Matthis Lueckmann, Richard Gao, Jakob H. Macke

- **Group equivariant neural posterior estimation** [[arXiv]](https://arxiv.org/abs/2111.13139)  
Maximilian Dax, Stephen R. Green, Jonathan Gair, Michael Deistler, Bernhard Schölkopf, Jakob H. Macke

- **A Trust Crisis In Simulation-Based Inference? Your Posterior Approximations Can Be Unfaithful** [[arXiv]](https://arxiv.org/abs/2110.06581)  
Joeri Hermans, Arnaud Delaunoy, François Rozet, Antoine Wehenkel, Volodimir Begy, Gilles Louppe

- **Arbitrary Marginal Neural Ratio Estimation for Simulation-based Inference** [[arXiv]](https://arxiv.org/abs/2110.00449)  
François Rozet, Gilles Louppe

- **Truncated Marginal Neural Ratio Estimation** [[arXiv]](https://arxiv.org/abs/2107.01214)  [[Code]](https://github.com/undark-lab/swyft/)  
Benjamin Kurt Miller, Alex Cole, Patrick Forré, Gilles Louppe, Christoph Weniger

- **MINIMALIST: Mutual INformatIon Maximization for Amortized Likelihood Inference from Sampled Trajectories** [[arXiv]](https://arxiv.org/abs/2106.01808)  
Giulio Isacchini, Natanael Spisak, Armita Nourmohammad, Thierry Mora, Aleksandra M. Walczak

- **Simulation-Based Inference with Approximately Correct Parameters via Maximum Entropy** [[arXiv]](https://arxiv.org/abs/2104.09668)  
Rainier Barrett, Mehrad Ansari, Gourab Ghoshal, Andrew D White

- **Sequential Neural Posterior and Likelihood Approximation** [[arXiv]](https://arxiv.org/abs/2102.06522)  
Samuel Wiqvist, Jes Frellsen, Umberto Picchini

- **Diagnostics for Conditional Density Models and Bayesian Inference Algorithms** [[arXiv]](https://arxiv.org/abs/2102.10473)  
David Zhao, Niccolò Dalmasso, Rafael Izbicki, Ann B. Lee

- **HNPE: Leveraging Global Parameters for Neural Posterior Estimation** [[arXiv]](https://arxiv.org/abs/2102.06477)  
Pedro L. C. Rodrigues, Thomas Moreau, Gilles Louppe, Alexandre Gramfort

- **Benchmarking Simulation-Based Inference** [[arXiv]](https://arxiv.org/abs/2101.04653)  
Jan-Matthis Lueckmann, Jan Boelts, David S. Greenberg, Pedro J. Gonçalves, Jakob H. Macke

- **Solving high-dimensional parameter inference: marginal posterior densities & Moment Networks** [[arXiv]](https://arxiv.org/abs/2011.05991)  
Niall Jeffrey, Benjamin D. Wandelt

- **Neural Empirical Bayes: Source Distribution Estimation and its Applications to Simulation-Based Inference** [[arXiv]](https://arxiv.org/abs/2011.05836)  
Maxime Vandegar, Michael Kagan, Antoine Wehenkel, Gilles Louppe

- **Neural Approximate Sufficient Statistics for Implicit Models** [[arXiv]](https://arxiv.org/abs/2010.10079)  
Yanzhi Chen, Dinghuai Zhang, Michael Gutmann, Aaron Courville, Zhanxing Zhu

- **Differentiable Likelihoods for Fast Inversion of 'Likelihood-Free' Dynamical Systems** [[arXiv]](https://arxiv.org/abs/2002.09301)  
Hans Kersting, Nicholas Krämer, Martin Schiegg, Christian Daniel, Michael Tiemann, Philipp Hennig

- **On Contrastive Learning for Likelihood-free Inference** [[arXiv]](https://arxiv.org/abs/2002.03712)  
Conor Durkan, Iain Murray, George Papamakarios

- **Automatic Posterior Transformation for Likelihood-Free Inference** [[arXiv]](https://arxiv.org/abs/1905.07488)  
David S. Greenberg, Marcel Nonnenmacher, Jakob H. Macke

- **Likelihood-free MCMC with Amortized Approximate Ratio Estimators** [[arXiv]](https://arxiv.org/abs/1903.04057)  
Joeri Hermans, Volodimir Begy, Gilles Louppe

- **Dynamic Likelihood-free Inference via Ratio Estimation (DIRE)** [[arXiv]](https://arxiv.org/abs/1810.09899)  
Traiko Dinev, Michael U. Gutmann

- **Likelihood-free inference with an improved cross-entropy estimator** [[arXiv]](https://arxiv.org/abs/1808.00973)  
Markus Stoye, Johann Brehmer, Gilles Louppe, Juan Pavez, Kyle Cranmer

- **Mining gold from implicit models to improve likelihood-free inference** [[arXiv]](https://arxiv.org/abs/1805.12244) [[Code]](https://github.com/johannbrehmer/simulator-mining-example)   
Johann Brehmer, Gilles Louppe, Juan Pavez, Kyle Cranmer

- **Likelihood-free inference with emulator networks** [[arXiv]](https://arxiv.org/abs/1805.09294)  
Jan-Matthis Lueckmann, Giacomo Bassetto, Theofanis Karaletsos, Jakob H. Macke

- **Sequential Neural Likelihood: Fast Likelihood-free Inference with Autoregressive Flows** [[arXiv]](https://arxiv.org/abs/1805.07226) [[Code]](https://github.com/gpapamak/snl)  
George Papamakarios, David C. Sterratt, Iain Murray

- **A Guide to Constraining Effective Field Theories with Machine Learning** [[arXiv]](https://arxiv.org/abs/1805.00020)  
Johann Brehmer, Kyle Cranmer, Gilles Louppe, Juan Pavez

- **Constraining Effective Field Theories with Machine Learning** [[arXiv]](https://arxiv.org/abs/1805.00013)  
Johann Brehmer, Kyle Cranmer, Gilles Louppe, Juan Pavez

- **Fast ε-free Inference of Simulation Models with Bayesian Conditional Density Estimation** [[arXiv]](https://arxiv.org/abs/1605.06376)  
George Papamakarios, Iain Murray

- **Approximating Likelihood Ratios with Calibrated Discriminative Classifiers** [[arXiv]](https://arxiv.org/abs/1506.02169)  
Kyle Cranmer, Juan Pavez, Gilles Louppe


# Application

## Cosmology, astrophysics, and astronomy

## Particle physics

## Neuroscience

## Evolutionary biology and genetics

## Other