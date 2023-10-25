# CS/ME 598 SML, Fall 2023: Scientific Machine Learning

## Course info:
* Mondays and Wednesdays, 11-12:15
* Location: DCL 1265
* Instructors:
  * Prof. Luke Olson, http://lukeo.cs.illinois.edu/
  * Prof. Matt West, https://lagrange.mechse.illinois.edu/
  * <span style="color:red">Are you looking to join the class?</span>   Unfortunately the class is full!  Auditing and sitting in on the class cannot be accommodated.  Sorry! (In future semesters we are hoping to expand the offering.)

## Course links:
* Public access repo (here): https://github.com/lukeolson-group/598sml-f23-syllabus
* Public access repo through Colab: https://colab.research.google.com/github/lukeolson-group/598sml-f23-syllabus
* Private class repo: https://github.com/lukeolson-group/598sml-f23-hw
* Slack: https://598sml-f23.slack.com/

## Course blurb

Familiarity with introductory numerical methods (e.g., CS 357 or TAM 470) and
is a prerequisite, preferably with some experience with numerical PDEs. The
course will cover the theory and practice of Scientific Machine Learning
(SciML), which leverages machine learning tools for scientific computing.
Topics include learning-based methods for differential equations, neural ODEs
and PDEs, physics-informed networks and model discovery, interpretable and
explainable learning, differentiable and probabilistic programming for
scientific computing, and uncertainty quantification via learning. Efficient
parallel implementation of algorithms on scalable computing architectures will
be emphasized.

## What to expect

The course requires some background in numerical methods (e.g. CS357, CS450, or
TAM 470 type courses), but no prior knowledge of machine learning or experience
with neural networks.  As such, the course will build the necessary tools through
the semester, with a focus on scientific applications.

The course is project based, particularly the last half.  You will use `git`,
`pytorch`, and `latex` to develop various examples and steps toward your final
project.

Assignments will be submitted on the [internal GitHub repository](https://github.com/lukeolson-group/598sml-f23-hw)

## On COVID and the class

While face coverings are not required in classrooms (current as of 08/23) we
fully support your decision to wear one if you wish.

If you test positive for COVID, then you should not attend class.

If you have any cold-like symptoms or do not feel well, then you should not
attend class, regardless of testing negative or positive for COVID.

In either case, your missed attendance due to illness will not impact
your grade in the course and we will work with you keep you up-to-date
on the material.

## Notes:

- [0828 automatic differentiation](./lectures/598sml-0828.pdf)
- [0830 implementing AD by hand](./lectures/598sml-0830.pdf)
- [0904 computation graph](./lectures/598sml-0904.pdf)
- [0911 PINNs](./lectures/598sml-0911.pdf)
- [0925 domain decomp](./lectures/598sml-0925.pdf)
- [0927 conservation laws, CPINNS](./lectures/598sml-0927.pdf)

## Notebooks:

- Public access repo (here): https://github.com/lukeolson-group/598sml-f23-syllabus/hw
- Public access repo through Colab: https://colab.research.google.com/github/lukeolson-group/598sml-f23-syllabus

## Schedule

- `week01 (0821)`
  - M: What is Sci ML? And what is this course?
    - [Scientific discovery in the age of artificial intelligence](https://www.nature.com/articles/s41586-023-06221-2)
    - [FourCastNet: A Global Data-driven High-resolution Weather Model using Adaptive Fourier Neural Operators](https://dl.acm.org/doi/abs/10.1145/3592979.3593412)
    - [GraphCast: Learning skillful medium-range global weather forecasting](https://arxiv.org/abs/2212.12794)
    - [Skilful precipitation nowcasting using deep generative models of radar](https://www.nature.com/articles/s41586-021-03854-z)
    - [Nowcasting the next hour of rain](https://www.deepmind.com/blog/nowcasting-the-next-hour-of-rain)
    - [Highly accurate protein structure prediction with AlphaFold](https://www.nature.com/articles/s41586-021-03819-2)
    - [‘It will change everything’: DeepMind’s AI makes gigantic leap in solving protein structures](https://www.nature.com/articles/d41586-020-03348-4)
  - W: Overview of tools
      - [Github's overview](https://docs.github.com/get-started)
      - [Github on git](https://docs.github.com/en/get-started/using-git/about-git)
      - [How git works](https://eagain.net/articles/git-for-computer-scientists/)
      - [How git works](https://www.cduan.com/technical/git/)
      - [Best practices](http://sethrobertson.github.io/GitBestPractices/)
      - [Python main docs](https://docs.python.org/)
      - [Python official tutorial](https://docs.python.org/3/tutorial/index.html)
- `week02 (0828)`
  - M: Automatic differentiation
      - [Automatic Differentiation in Machine Learning: a Survey](https://arxiv.org/pdf/1502.05767.pdf)
      - [Calculus on Computational Graphs: Backpropagation](http://colah.github.io/posts/2015-08-Backprop/)
      - [Automatic differentiation in PyTorch](https://openreview.net/pdf?id=BJJsrmfCZ)
  - W: Implementing autodiff
      - https://sidsite.com/posts/autodiff/
- `week03 (0904)`
   - M: 0904, no class, Labor Day
   - W: Approximating functions
       - [Universal approximation theorem](https://en.wikipedia.org/wiki/Universal_approximation_theorem)
       - [Approximation theory of the MLP model in neural networks](https://www.cambridge.org/core/journals/acta-numerica/article/approximation-theory-of-the-mlp-model-in-neural-networks/18072C558C8410C4F92A82BCC8FC8CF9)
       - [Neural network approximation](https://www.cambridge.org/core/journals/acta-numerica/article/neural-network-approximation/7077A90FB36D405D903DCC82683B7A48)
- `week04 (0911)`
  - M: PINNs
  - W: PINN implementations
- `week05 (0918)`
  - M: CPINNS
  - W: XPINNS and Domain Decomposition
- `week06 (0925)`
  - M: Domain decomposition, elliptic PDEs
  - W: Domain decomposition, elliptic PDEs
- `week07 (1002)`
  - M: Integral Equations, `prj00` start
  - W: Domain decomposition, HAL, `prj00` due.
- `week08 (1009)`
  - M: `prj01` project description due; work on `proj02` workflow
  - W: Neural ODEs
- `week09 (1016)`
  - M: workon code for projects, hw
  - W: `prj03` project setup and initial results, Neural ODEs (due Friday 10/23)
  - W: DeepONets
- `week10 (1023)`
  - M: Gaussian Processes
  - W: Present training results, `prj04` summarize model, loss, training (due Friday 10/27)
  - W: Neural Operators
- `week11 (1030)`
  - M: Project peer feedback `prj05`
  - W: Graph Neural Networks
- `week12 (1106)`
  - M: Share training results `prj06` statrt
  - W: Specialized talk
- `week13 (1113)`
  - M: Draft slides, results, `prj06` due
  - W: Paper reading
- `week14 (1120)` ~~Thanksgiving~~
- `week15 (1127)`
    M: `proj07` final slides due
  - M: Presentations day 1
  - W: Presentations day 2
- `week16 (1204)`
  - M: Presentations day 3
  - W: Presentations day 4

## Grading

Final course scores will be computed as 40% weekly Homeworks and 60% Final Project.
