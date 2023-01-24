<h1 align="center">
Awesome Neural SBI<!-- omit from toc -->
</h1>

<h4 align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](https://opensource.org/licenses/MIT)
[![Pull requests welcome](https://img.shields.io/badge/Pull%20Requests-welcome-green.svg?logo=github)](https://github.com/smsharma/awesome-neural-sbi)
</h4>

A community-sourced list of papers and resources on neural simulation-based inference, covering both methodological developments and domain applications. Given the nature of the field, the list is bound to be highly incomplete -- contributions are welcome!

# Contents<!-- omit from toc -->

- [Software and Resources](#software-and-resources)
  - [Code Packages and Benchmarks](#code-packages-and-benchmarks)
  - [Review Papers](#review-papers)
  - [Discovery and Links](#discovery-and-links)
- [Papers: Methods](#papers-methods)
- [Papers: Application](#papers-application)
  - [Cosmology, Astrophysics, and Astronomy](#cosmology-astrophysics-and-astronomy)
  - [Particle Physics](#particle-physics)
  - [Neuroscience](#neuroscience)
  - [Health and Medicine](#health-and-medicine)
  - [Other Domains](#other-domains)
  - [Application to Real Data](#application-to-real-data)

# Software and Resources
  
## Code Packages and Benchmarks

- `sbi` [[Code]](https://github.com/mackelab/sbi) [[Docs]](https://www.mackelab.org/sbi/) [[Paper]](https://joss.theoj.org/papers/10.21105/joss.02505): General-purpose simulation-based inference toolkit.
- `sbibm` [[Code]](https://github.com/sbi-benchmark/sbibm) [[Docs]](https://sbi-benchmark.github.io/) [[Paper]](https://arxiv.org/abs/2101.04653): Simulation-based inference benchmarking framework.
- `swyft` [[Code]](https://github.com/undark-lab/swyft) [[Docs]](https://swyft.readthedocs.io/en/latest/) [[Paper]](https://joss.theoj.org/papers/10.21105/joss.04205): Official implementation of Truncated Marginal Neural Ratio Estimation (TMNRE), a hyper-efficient, simulation-based inference technique for complex data and expensive simulators. 
- `lampe` [[Code]](https://github.com/francois-rozet/lampe) [[Docs]](https://francois-rozet.github.io/lampe/): Likelihood-free AMortized Posterior Estimation with PyTorch.
- `MadMiner` [[Code]](https://github.com/madminer-tool/madminer) [[Docs]](https://madminer.readthedocs.io/en/latest/index.html) [[Paper]](https://arxiv.org/abs/1907.10621): Machine learning–based inference toolkit for particle physics.
- `pydelfi` [[Code]](https://github.com/justinalsing/pydelfi) [[Docs]](https://pydelfi.readthedocs.io/en/latest/intro.html) [[Paper]](https://arxiv.org/abs/1903.00007): Early implementation of Density Estimation Likelihood-Free Inference (DELFI) with neural density estimators and adaptive acquisition of simulations.
- `carl` [[Code]](https://github.com/diana-hep/carl) [[Docs]](http://diana-hep.org/carl/) [[Paper]](https://joss.theoj.org/papers/10.21105/joss.00011): Early toolbox for neural network-based likelihood-free inference in Python.

## Review Papers

- **The frontier of simulation-based inference** [[arXiv]](https://arxiv.org/abs/1911.01429)  
Kyle Cranmer, Johann Brehmer, Gilles Louppe

## Discovery and Links

- [arXiv search](https://arxiv.org/search/advanced?advanced=1&terms-0-operator=AND&terms-0-term=%22simulation-based+inference%22+&terms-0-field=all&terms-1-operator=OR&terms-1-term=%22likelihood-free+inference%22&terms-1-field=all&classification-computer_science=y&classification-mathematics=y&classification-physics=y&classification-physics_archives=all&classification-q_biology=y&classification-statistics=y&classification-include_cross_list=include&date-filter_by=all_dates&date-year=&date-from_date=&date-to_date=&date-date_type=submitted_date&abstracts=show&size=50&order=-announced_date_first) for "simulation-based inference" or "likelihood-free inference"
- [Google Scholar search](https://scholar.google.com/scholar?hl=en&scisbd=1&as_sdt=0%2C22&q=%22simulation-based+inference%22+OR+%22likelihood-free+inference%22&btnG=) for "simulation-based inference" or "likelihood-free inference"
- [simulation-based-inference.org](http://simulation-based-inference.org/)

# Papers: Methods
*Methodological and use-inspired papers. Listed in reverse-chronological order.*

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

- **New Machine Learning Techniques for Simulation-Based Inference: InferoStatic Nets, Kernel Score Estimation, and Kernel Likelihood Ratio Estimation** [[arXiv]](https://arxiv.org/abs/2210.01680)  
Kyoungchul Kong, Konstantin T. Matchev, Stephen Mrenna, Prasanth Shyamsundar

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

- **Likelihood-Free Frequentist Inference: Confidence Sets with Correct Conditional Coverage** [[arXiv]](https://arxiv.org/abs/2107.03920)  
Niccolò Dalmasso, Luca Masserano, David Zhao, Rafael Izbicki, Ann B. Lee

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

- **Fast ε-free Inference of Simulation Models with Bayesian Conditional Density Estimation** [[arXiv]](https://arxiv.org/abs/1605.06376)  
George Papamakarios, Iain Murray

- **Approximating Likelihood Ratios with Calibrated Discriminative Classifiers** [[arXiv]](https://arxiv.org/abs/1506.02169)  
Kyle Cranmer, Juan Pavez, Gilles Louppe

# Papers: Application
*Domain application of neural simulation-based inference. Papers listed in reverse-chronological order.*

## Cosmology, Astrophysics, and Astronomy

- **Neural posterior estimation for exoplanetary atmospheric retrieval** [[arXiv]](https://arxiv.org/abs/2301.06575)  
Malavika Vasist, François Rozet, Olivier Absil, Paul Mollière, Evert Nasedkin, Gilles Louppe

- **Debiasing Standard Siren Inference of the Hubble Constant with Marginal Neural Ratio Estimation** [[arXiv]](https://arxiv.org/abs/2301.05241)  
Samuel Gagnon-Hartman, John Ruan, Daryl Haggard

- **Calibrating cosmological simulations with implicit likelihood inference using galaxy growth observables** [[arXiv]](https://arxiv.org/abs/2211.16461)  
Yongseok Jo et al

- **DIGS: Deep Inference of Galaxy Spectra with Neural Posterior Estimation** [[arXiv]](https://arxiv.org/abs/2211.09126)  
Gourav Khullar, Brian Nord, Aleksandra Ciprijanovic, Jason Poh, Fei Xu

- **Detection is truncation: studying source populations with truncated marginal neural ratio estimation** [[arXiv]](https://arxiv.org/abs/2211.04291)  
Noemi Anau Montel, Christoph Weniger

- **SIMBIG : A Forward Modeling Approach To Analyzing Galaxy Clustering** [[arXiv]](https://arxiv.org/abs/2211.00723)  
ChangHoon Hahn et al

- **Neural Importance Sampling for Rapid and Reliable Gravitational-Wave Inference** [[arXiv]](https://arxiv.org/abs/2210.05686)  
Maximilian Dax, Stephen R. Green, Jonathan Gair, Michael Pürrer, Jonas Wildberger, Jakob H. Macke, Alessandra Buonanno, Bernhard Schölkopf

- **One never walks alone: the effect of the perturber population on subhalo measurements in strong gravitational lenses** [[arXiv]](https://arxiv.org/abs/2209.09918)  
Adam Coogan, Noemi Anau Montel, Konstantin Karchev, Meiert W. Grootes, Francesco Nattino, Christoph Weniger

- **SICRET: Supernova Ia Cosmology with truncated marginal neural Ratio EsTimation** [[arXiv]](https://arxiv.org/abs/2209.06733)  
Konstantin Karchev, Roberto Trotta, Christoph Weniger

- **Inferring subhalo effective density slopes from strong lensing observations with neural likelihood-ratio estimation** [[arXiv]](https://arxiv.org/abs/2208.13796)  
Gemma Zhang, Siddharth Mishra-Sharma, Cora Dvorkin

- **Uncovering dark matter density profiles in dwarf galaxies with graph neural networks** [[arXiv]](https://arxiv.org/abs/2208.12825)  
Tri Nguyen, Siddharth Mishra-Sharma, Reuel Williams, Lina Necib

- **Estimating Cosmological Constraints from Galaxy Cluster Abundance using Simulation-Based Inference** [[arXiv]](https://arxiv.org/abs/2208.00134)  
Moonzarin Reza, Yuanyuan Zhang, Brian Nord, Jason Poh, Aleksandra Ciprijanovic, Louis Strigari

- **Towards reconstructing the halo clustering and halo mass function of N-body simulations using neural ratio estimation** [[arXiv]](https://arxiv.org/abs/2206.11312)  
Androniki Dimitriou, Christoph Weniger, Camila A. Correa

- **Estimating the warm dark matter mass from strong lensing images with truncated marginal neural ratio estimation** [[arXiv]](https://arxiv.org/abs/2205.09126)  
Noemi Anau Montel, Adam Coogan, Camila Correa, Konstantin Karchev, Christoph Weniger

- **Implicit Likelihood Inference of Reionization Parameters from the 21 cm Power Spectrum** [[arXiv]](https://arxiv.org/abs/2203.15734)  
Xiaosheng Zhao, Yi Mao, Benjamin D. Wandelt

- **Accelerated Bayesian SED Modeling using Amortized Neural Posterior Estimation** [[arXiv]](https://arxiv.org/abs/2203.07391)  
ChangHoon Hahn, Peter Melchior

- **Simulation-Based Inference of Strong Gravitational Lensing Parameters** [[arXiv]](https://arxiv.org/abs/2112.05278)  
Ronan Legin, Yashar Hezaveh, Laurence Perreault Levasseur, Benjamin Wandelt

- **Fast and Credible Likelihood-Free Cosmology with Truncated Marginal Neural Ratio Estimation** [[arXiv]](https://arxiv.org/abs/2111.08030)  
Alex Cole, Benjamin Kurt Miller, Samuel J. Witte, Maxwell X. Cai, Meiert W. Grootes, Francesco Nattino, Christoph Weniger

- **A neural simulation-based inference approach for characterizing the Galactic Center γ-ray excess** [[arXiv]](https://arxiv.org/abs/2110.06931)  
Siddharth Mishra-Sharma, Kyle Cranmer

- **Inferring dark matter substructure with astrometric lensing beyond the power spectrum** [[arXiv]](https://arxiv.org/abs/2110.01620)  
Siddharth Mishra-Sharma

- **Approximate Bayesian Neural Doppler Imaging** [[arXiv]](https://arxiv.org/abs/2108.09266)  
A. Asensio Ramos, C. Diaz Baso, O. Kochukhov

- **Lossless, Scalable Implicit Likelihood Inference for Cosmological Fields** [[arXiv]](https://arxiv.org/abs/2107.07405)  
T. Lucas Makinen, Tom Charnock, Justin Alsing, Benjamin D. Wandelt

- **Real-time gravitational-wave science with neural posterior estimation** [[arXiv]](https://arxiv.org/abs/2106.12594)  
Maximilian Dax, Stephen R. Green, Jonathan Gair, Jakob H. Macke, Alessandra Buonanno, Bernhard Schölkopf

- **Real-Time Likelihood-Free Inference of Roman Binary Microlensing Events with Amortized Neural Posterior Estimation** [[arXiv]](https://arxiv.org/abs/2102.05673)  
Keming Zhang, Joshua S. Bloom, B. Scott Gaudi, Francois Lanusse, Casey Lam, Jessica R. Lu

- **Towards constraining warm dark matter with stellar streams through neural simulation-based inference** [[arXiv]](https://arxiv.org/abs/2011.14923)  
Joeri Hermans, Nilanjan Banik, Christoph Weniger, Gianfranco Bertone, Gilles Louppe

- **Lightning-Fast Gravitational Wave Parameter Inference through Neural Amortization** [[arXiv]](https://arxiv.org/abs/2010.12931)  
Arnaud Delaunoy, Antoine Wehenkel, Tanja Hinderer, Samaya Nissanke, Christoph Weniger, Andrew R. Williamson, Gilles Louppe

- **The sum of the masses of the Milky Way and M31: a likelihood-free inference approach** [[arXiv]](https://arxiv.org/abs/2010.08537)  
Pablo Lemos, Niall Jeffrey, Lorne Whiteway, Ofer Lahav, Niam I Libeskind, Yehuda Hoffman

- **Likelihood-free inference with neural compression of DES SV weak lensing map statistics** [[arXiv]](https://arxiv.org/abs/2009.08459)  
Niall Jeffrey, Justin Alsing, François Lanusse

- **Mining for Dark Matter Substructure: Inferring subhalo population properties from strong lenses with machine learning** [[arXiv]](https://arxiv.org/abs/1909.02005)  
Johann Brehmer, Siddharth Mishra-Sharma, Joeri Hermans, Gilles Louppe, Kyle Cranmer

- **Fast likelihood-free cosmology with neural density estimators and active learning** [[arXiv]](https://arxiv.org/abs/1903.00007)  
Justin Alsing, Tom Charnock, Stephen Feeney, Benjamin Wandelt

## Particle Physics

- **Simulation-based inference methods for particle physics** [[arXiv]](https://arxiv.org/abs/2010.06439)  
Johann Brehmer, Kyle Cranmer

- **MadMiner: Machine learning-based inference for particle physics** [[arXiv]](https://arxiv.org/abs/1907.10621)  
Johann Brehmer, Felix Kling, Irina Espejo, Kyle Cranmer

- **Etalumis: Bringing Probabilistic Programming to Scientific Simulators at Scale** [[arXiv]](https://arxiv.org/abs/1907.03382)  
Atılım Güneş Baydin et al

- **Constraining Effective Field Theories with Machine Learning** [[arXiv]](https://arxiv.org/abs/1805.00013)  
Johann Brehmer, Kyle Cranmer, Gilles Louppe, Juan Pavez

## Neuroscience

- **Likelihood approximation networks (LANs) for fast inference of simulation models in cognitive neuroscience** [[Paper]](https://elifesciences.org/articles/65074)  
Alexander Fengler, Lakshmi N Govindarajan, Tony Chen, Michael J Frank

- **Training deep neural density estimators to identify mechanistic models of neural dynamics** [[Paper]](https://elifesciences.org/articles/56261)  
Pedro J Gonçalves et al

- **Amortized Bayesian Inference for Models of Cognition** [[arXiv]](https://arxiv.org/abs/2005.03899)  
Stefan T. Radev, Andreas Voss, Eva Marie Wieschen, Paul-Christian Bürkner

## Health and Medicine

- **Mutation rate, selection, and epistasis inferred from RNA virus haplotypes via neural posterior estimation** [[bioRxiv]](https://www.biorxiv.org/content/10.1101/2023.01.09.523230v1.abstract)  
Itamar Caspi, Moran Meir, Nadav Ben Nun, Uri Yakhini, Adi Stern,  Yoav Ram

- **Simulation-Based Inference for Whole-Brain Network Modeling of Epilepsy using Deep Neural Density Estimators** [[medRxiv]](https://www.medrxiv.org/content/10.1101/2022.06.02.22275860v1)  
Meysam Hashemi, Anirudh N. Vattikonda, Jayant Jha, Viktor Sip, Marmaduke M. Woodman, Fabrice Bartolomei, Viktor K. Jirsa

- **Simulation-Based Inference for Global Health Decisions** [[arXiv]](https://arxiv.org/abs/2005.07062)  
Christian Schroeder de Witt et al

## Other Domains
*Applications where multiple papers could not be grouped under a single heading.*

- **Simulation-based inference of single-molecule force spectroscopy** [[arXiv]](https://arxiv.org/abs/2209.10392)  
Lars Dingeldein, Pilar Cossio, Roberto Covino

- **Normalizing flows for likelihood-free inference with fusion simulations** [[Paper]](https://iopscience.iop.org/article/10.1088/1361-6587/ac828d)  
C S Furia, R M Churchill

- **Amortized Bayesian Inference of GISAXS Data with Normalizing Flows** [[arXiv]](https://arxiv.org/abs/2210.01543)  
Maksim Zhdanov, Lisa Randolph, Thomas Kluge, Motoaki Nakatsutsumi, Christian Gutt, Marina Ganeva, Nico Hoffmann

- **Optimal Design of Experiments for Simulation-Based Inference of Mechanistic Acyclic Biological Networks** [[arXiv]](https://arxiv.org/abs/2111.13612)  
Vincent Zaballa, Elliot Hui

- **Simulation-based Bayesian inference for multi-fingered robotic grasping** [[arXiv]](https://arxiv.org/abs/2109.14275)  
Norman Marlier, Olivier Brüls, Gilles Louppe

- **Simulation-based inference of evolutionary parameters from adaptation dynamics using neural networks** [[bioRxiv]](https://www.biorxiv.org/content/10.1101/2021.09.30.462581v1.abstract)  
Grace Avecilla, Julie N. Chuong, Fangfei Li, Gavin Sherlock, David Gresham, Yoav Ram

## Application to Real Data
*Applications of neural simulation-based inference beyond synthetic data.*

- **SIMBIG : A Forward Modeling Approach To Analyzing Galaxy Clustering** [[arXiv]](https://arxiv.org/abs/2211.00723)  
ChangHoon Hahn et al

- **A neural simulation-based inference approach for characterizing the Galactic Center γ-ray excess** [[arXiv]](https://arxiv.org/abs/2110.06931)  
Siddharth Mishra-Sharma, Kyle Cranmer

- **Towards constraining warm dark matter with stellar streams through neural simulation-based inference** *(Preliminary)* [[arXiv]](https://arxiv.org/abs/2011.14923)  
Joeri Hermans, Nilanjan Banik, Christoph Weniger, Gianfranco Bertone, Gilles Louppe

- **Likelihood-free inference with neural compression of DES SV weak lensing map statistics** [[arXiv]](https://arxiv.org/abs/2009.08459)  
Niall Jeffrey, Justin Alsing, François Lanusse
